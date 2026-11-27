---
api_specs:
- filename: bnsf-automotive-api-openapi.yml
  format: yaml
  label: BNSF AUTOMOTIVE API
  slug: bnsf-automotive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bnsf/openapi/bnsf-automotive-api-openapi.yml
- filename: bnsf-carload-api-openapi.yml
  format: yaml
  label: BNSF CARLOAD API
  slug: bnsf-carload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bnsf/openapi/bnsf-carload-api-openapi.yml
- filename: bnsf-intermodal-api-openapi.yml
  format: yaml
  label: BNSF INTERMODAL API
  slug: bnsf-intermodal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bnsf/openapi/bnsf-intermodal-api-openapi.yml
- filename: bnsf-requests-api-openapi.yml
  format: yaml
  label: BNSF Requests API
  slug: bnsf-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bnsf/openapi/bnsf-requests-api-openapi.yml
- filename: bnsf-trains-api-openapi.yml
  format: yaml
  label: BNSF TRAINS API
  slug: bnsf-trains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bnsf/openapi/bnsf-trains-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: accessing them from jurisdictions where their contents are illegal is prohibited
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only
    text: except solely for business purposes in support of your business relationship with BNSF, for non-commercial purposes only;
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
name: BNSF
provenance_date: '2026-11-09'
provider_name: BNSF
provider_slug: bnsf
slug: bnsf-eligibility
source_date: '2026-11-09'
source_filename: bnsf-eligibility.yml
source_heading: Eligibility
source_page: https://www.bnsf.com/site-terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BNSF\naid: bnsf\nurl: https://www.bnsf.com/site-terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: accessing them from jurisdictions where their contents are illegal is prohibited\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: except solely for business purposes in support of your business relationship with BNSF, for non-commercial\n    purposes only;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bnsf/eligibility/bnsf-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from BNSF's own page on 2026-11-09.
synthetic: false
tags:
- Freight
- Railroad
- Rail
- Shipping
- Trains
- Intermodal
- Logistics
- Supply Chain
- Transportation
---
