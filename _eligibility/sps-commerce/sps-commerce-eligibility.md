---
api_specs:
- filename: sps-commerce-submission-api-openapi.yml
  format: yaml
  label: SPS Commerce Trading Partner Submission API
  slug: sps-commerce-trading-partner-submission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sps-commerce/openapi/sps-commerce-submission-api-openapi.yml
- filename: sps-commerce-inventory-api-openapi.yml
  format: yaml
  label: SPS Commerce Inventory API
  slug: sps-commerce-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sps-commerce/openapi/sps-commerce-inventory-api-openapi.yml
- filename: sps-commerce-import-api-openapi.yml
  format: yaml
  label: SPS Commerce Import API
  slug: sps-commerce-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sps-commerce/openapi/sps-commerce-import-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Products, Services, and technology are subject to U.S. export laws and may not be exported to certain countries or end-users.
  entity_types:
  - text: You agree to limit such uses to your internal business purposes and will not resell or sublicense the Services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No substitute for human judgment in high-stakes decisions
    text: use any AI Feature as a substitute for human judgment in making legally binding, regulatory, safety-critical, or high-risk business decisions.
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
name: SPS Commerce
provenance_date: '2026-11-10'
provider_name: SPS Commerce
provider_slug: sps-commerce
slug: sps-commerce-eligibility
source_date: '2026-11-10'
source_filename: sps-commerce-eligibility.yml
source_heading: Eligibility
source_page: https://www.spscommerce.com/about/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SPS Commerce\naid: sps-commerce\nurl: https://www.spscommerce.com/about/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Products, Services, and technology are subject to U.S. export laws and may not be exported to certain\n    countries or end-users.\nentity_types:\n- type: business\n  text: You agree to limit such uses to your internal business purposes and will not resell or sublicense the Services.\nrestricted_uses:\n- summary: No substitute for human judgment in high-stakes decisions\n  text: use any AI Feature as a substitute for human judgment in making legally\
  \ binding, regulatory, safety-critical,\n    or high-risk business decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sps-commerce/eligibility/sps-commerce-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from SPS Commerce's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EDI
- Retail
- Supply Chain
- Commerce
- Trading Partners
- API Standards
---
