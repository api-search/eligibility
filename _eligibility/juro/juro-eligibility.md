---
api_specs:
- filename: juro-contracts-api-openapi.yml
  format: yaml
  label: Juro Contracts API
  slug: juro-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/juro/openapi/juro-contracts-api-openapi.yml
- filename: juro-health-api-openapi.yml
  format: yaml
  label: Juro Health API
  slug: juro-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/juro/openapi/juro-health-api-openapi.yml
- filename: juro-signatures-api-openapi.yml
  format: yaml
  label: Juro Signatures API
  slug: juro-signatures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/juro/openapi/juro-signatures-api-openapi.yml
- filename: juro-templates-api-openapi.yml
  format: yaml
  label: Juro Templates API
  slug: juro-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/juro/openapi/juro-templates-api-openapi.yml
- filename: juro-webhooks-api-openapi.yml
  format: yaml
  label: Juro Webhooks API
  slug: juro-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/juro/openapi/juro-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: using our API on behalf of a business or organisation
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: You must not use our API for any unlawful purpose
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
name: Juro
provenance_date: '2026-11-09'
provider_name: Juro
provider_slug: juro
slug: juro-eligibility
source_date: '2026-11-09'
source_filename: juro-eligibility.yml
source_heading: Eligibility
source_page: https://juro.com/terms/api-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Juro\naid: juro\nurl: https://juro.com/terms/api-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: using our API on behalf of a business or organisation\nrestricted_uses:\n- summary: Unlawful use\n  text: You must not use our API for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/juro/eligibility/juro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Juro's own page on 2026-11-09.
synthetic: false
tags:
- Contract Management
- Contract Lifecycle Management
- Contract Automation
- Legal
- Legal Tech
- E-Signature
- Contracts
---
