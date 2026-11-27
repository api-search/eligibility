---
api_specs:
- filename: wisepim-gtin-api-openapi.yml
  format: yaml
  label: WISEPIM Open Data API GTIN API
  slug: wisepim-gtin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wisepim/openapi/wisepim-gtin-api-openapi.yml
- filename: wisepim-hs-codes-api-openapi.yml
  format: yaml
  label: WISEPIM Open Data API HS codes API
  slug: wisepim-hs-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wisepim/openapi/wisepim-hs-codes-api-openapi.yml
- filename: wisepim-marketplace-fees-api-openapi.yml
  format: yaml
  label: WISEPIM Open Data API Marketplace fees API
  slug: wisepim-marketplace-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wisepim/openapi/wisepim-marketplace-fees-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be authorized to act on behalf of your organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal data
    text: you agree not to upload, store, or process personal data of individuals (such as customer, consumer, or end-user personal data) in the Service
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
name: WISEPIM Open Data API
provenance_date: '2026-11-10'
provider_name: WISEPIM Open Data API
provider_slug: wisepim
slug: wisepim-eligibility
source_date: '2026-11-10'
source_filename: wisepim-eligibility.yml
source_heading: Eligibility
source_page: https://wisepim.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WISEPIM Open Data API\naid: wisepim\nurl: https://wisepim.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Be authorized to act on behalf of your organization\nrestricted_uses:\n- summary: No personal data\n  text: you agree not to upload, store, or process personal data of individuals (such as customer, consumer, or\n    end-user personal data) in the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wisepim/eligibility/wisepim-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from WISEPIM Open Data API's own page on 2026-11-10.
synthetic: false
tags:
- Product Information Management
- Artificial Intelligence
- E-Commerce
- Catalog Enrichment
- Translation
- Wholesale
- Retail
---
