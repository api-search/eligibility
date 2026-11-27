---
api_specs:
- filename: arkose-labs-edge-api-openapi.yml
  format: yaml
  label: Arkose Labs Edge API
  slug: arkose-labs-edge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkose-labs/openapi/arkose-labs-edge-api-openapi.yml
- filename: arkose-labs-schema-api-openapi.yml
  format: yaml
  label: Arkose Labs Schema API
  slug: arkose-labs-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkose-labs/openapi/arkose-labs-schema-api-openapi.yml
- filename: arkose-labs-verify-api-openapi.yml
  format: yaml
  label: Arkose Labs Verify API
  slug: arkose-labs-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkose-labs/openapi/arkose-labs-verify-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    value: legal age
  restricted_uses:
  - summary: Non-commercial use only
    text: You will only use the Services for your own internal, personal, non-commercial use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Arkose Labs
provenance_date: '2026-11-09'
provider_name: Arkose Labs
provider_slug: arkose-labs
slug: arkose-labs-eligibility
source_date: '2026-11-09'
source_filename: arkose-labs-eligibility.yml
source_heading: Eligibility
source_page: https://www.arkoselabs.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arkose Labs\naid: arkose-labs\nurl: https://www.arkoselabs.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You will only use the Services for\
  \ your own internal, personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\n"
source_yaml_url: https://artifacts.apis.io/arkose-labs/eligibility/arkose-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arkose Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Security
- Bot Management
- Fraud Prevention
- Authentication
- Account Security
- Bot Detection
- Risk Scoring
- CAPTCHA
---
