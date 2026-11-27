---
api_specs:
- filename: openapi.json
  format: json
  label: Bankstatemently API
  slug: bankstatemently-api
  spec_type: OpenAPI
  url: https://api.bankstatemently.com/v1/openapi.json
- filename: bankstatemently-com-v1-openapi.json
  format: json
  label: Bankstatemently API V1 API
  slug: bankstatemently-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankstatemently-com/openapi/_original/bankstatemently-com-v1-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Service on behalf of a company, you represent that you have the authority to bind that company to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Uploading documents without rights or consent
    text: You are responsible for ensuring that you have all necessary rights, permissions, and consents to upload and process documents using the Service
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
name: Bankstatemently
provenance_date: '2026-11-09'
provider_name: Bankstatemently
provider_slug: bankstatemently-com
slug: bankstatemently-com-eligibility
source_date: '2026-11-09'
source_filename: bankstatemently-com-eligibility.yml
source_heading: Eligibility
source_page: https://bankstatemently.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bankstatemently\naid: bankstatemently-com\nurl: https://bankstatemently.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Service on behalf of a company, you represent that you have the authority to bind\n    that company to these Terms.\nrestricted_uses:\n- summary: Uploading documents without rights or consent\n  text: You are responsible for ensuring that you have all necessary rights, permissions, and consents to upload\n    and process documents using the Service\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bankstatemently-com/eligibility/bankstatemently-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bankstatemently's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banking
- Data Conversion
- Software-as-a-Service
---
