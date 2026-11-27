---
api_specs:
- filename: carrierscrub-com-authority-history-api-openapi.yml
  format: yaml
  label: CarrierScrub Authority History API
  slug: carrierscrub-com-authority-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-authority-history-api-openapi.yml
- filename: carrierscrub-com-batch-api-openapi.yml
  format: yaml
  label: CarrierScrub Batch API
  slug: carrierscrub-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-batch-api-openapi.yml
- filename: carrierscrub-com-fmcsa-activity-api-openapi.yml
  format: yaml
  label: CarrierScrub Fmcsa Activity API
  slug: carrierscrub-com-fmcsa-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-fmcsa-activity-api-openapi.yml
- filename: carrierscrub-com-lookup-api-openapi.yml
  format: yaml
  label: CarrierScrub Lookup API
  slug: carrierscrub-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-lookup-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use CarrierScrub on behalf of a brokerage, you confirm you are authorized to bind it.
    type: business
  - text: You must be at least 18 years old.
    type: individual
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No FCRA-covered eligibility decisions
    text: You agree not to use any CarrierScrub result, in whole or in part, as a factor in deciding a person's eligibility for credit, insurance, employment, housing, or any other purpose the FCRA covers.
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
name: CarrierScrub
provenance_date: '2026-11-09'
provider_name: CarrierScrub
provider_slug: carrierscrub-com
slug: carrierscrub-com-eligibility
source_date: '2026-11-09'
source_filename: carrierscrub-com-eligibility.yml
source_heading: Eligibility
source_page: https://carrierscrub.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CarrierScrub\naid: carrierscrub-com\nurl: https://carrierscrub.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use CarrierScrub on behalf of a brokerage, you confirm you are authorized to bind it.\n- type: individual\n  text: You must be at least 18 years old.\nrestricted_uses:\n- summary: No FCRA-covered eligibility decisions\n  text: You agree not to use any CarrierScrub result, in whole or in part, as a factor in deciding a person's eligibility\n    for credit, insurance, employment, housing, or any other purpose\
  \ the FCRA covers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/carrierscrub-com/eligibility/carrierscrub-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CarrierScrub's own page on 2026-11-09.
synthetic: false
tags:
- carrier-vetting
- Freight Brokerage
- FMCSA Data
---
