---
api_specs:
- filename: entitylight-business-searches-api-openapi.yml
  format: yaml
  label: Entitylight Business Searches API
  slug: entitylight-business-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entitylight/openapi/entitylight-business-searches-api-openapi.yml
- filename: entitylight-lookups-api-openapi.yml
  format: yaml
  label: Entitylight Lookups API
  slug: entitylight-lookups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entitylight/openapi/entitylight-lookups-api-openapi.yml
- filename: entitylight-ofac-screenings-api-openapi.yml
  format: yaml
  label: Entitylight Ofac Screenings API
  slug: entitylight-ofac-screenings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entitylight/openapi/entitylight-ofac-screenings-api-openapi.yml
- filename: entitylight-ucc-searches-api-openapi.yml
  format: yaml
  label: Entitylight Ucc Searches API
  slug: entitylight-ucc-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entitylight/openapi/entitylight-ucc-searches-api-openapi.yml
- filename: entitylight-usage-api-openapi.yml
  format: yaml
  label: Entitylight Usage API
  slug: entitylight-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entitylight/openapi/entitylight-usage-api-openapi.yml
- filename: entitylight-watches-api-openapi.yml
  format: yaml
  label: Entitylight Watches API
  slug: entitylight-watches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entitylight/openapi/entitylight-watches-api-openapi.yml
- filename: entitylight-webhook-api-openapi.yml
  format: yaml
  label: Entitylight Webhook API
  slug: entitylight-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entitylight/openapi/entitylight-webhook-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: use Entitylight on behalf of a business
    type: business
  - text: You must be at least 18
    type: individual
  minimum_age:
    text: You must be at least 18 and use Entitylight on behalf of a business.
    value: '18'
  restricted_uses:
  - summary: No consumer eligibility decisions
    text: You may not use Entitylight, in whole or in part, to decide whether an individual is eligible for personal credit, insurance, employment, housing or any other purpose covered by those laws.
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
name: Entitylight
provenance_date: '2026-11-09'
provider_name: Entitylight
provider_slug: entitylight
slug: entitylight-eligibility
source_date: '2026-11-09'
source_filename: entitylight-eligibility.yml
source_heading: Eligibility
source_page: https://entitylight.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Entitylight\naid: entitylight\nurl: https://entitylight.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: use Entitylight on behalf of a business\n- type: individual\n  text: You must be at least 18\nrestricted_uses:\n- summary: No consumer eligibility decisions\n  text: You may not use Entitylight, in whole or in part, to decide whether an individual is eligible for personal\n    credit, insurance, employment, housing or any other purpose covered by those laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and use Entitylight on behalf of a business.\n"
source_yaml_url: https://artifacts.apis.io/entitylight/eligibility/entitylight-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Entitylight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Business
- UCC
- Litigation
- Monitoring
---
