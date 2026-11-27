---
api_specs:
- filename: deepinquiry-facts-api-openapi.yml
  format: yaml
  label: DeepInquiry Verified Facts API (Machine Accountability Corp) Facts API
  slug: deepinquiry-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepinquiry/openapi/deepinquiry-facts-api-openapi.yml
- filename: deepinquiry-search-api-openapi.yml
  format: yaml
  label: DeepInquiry Verified Facts API (Machine Accountability Corp) Search API
  slug: deepinquiry-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepinquiry/openapi/deepinquiry-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country subject to a U.S. government embargo, or that has been designated by the U.S. government as a "terrorist-supporting" country
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service (or 16 in the European Union and United Kingdom).
    value: '13'
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
name: DeepInquiry Verified Facts API (Machine Accountability Corp)
provenance_date: '2026-11-09'
provider_name: DeepInquiry Verified Facts API (Machine Accountability Corp)
provider_slug: deepinquiry
slug: deepinquiry-eligibility
source_date: '2026-11-09'
source_filename: deepinquiry-eligibility.yml
source_heading: Eligibility
source_page: https://www.deepinquiry.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeepInquiry Verified Facts API (Machine Accountability Corp)\naid: deepinquiry\nurl: https://www.deepinquiry.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country subject to a U.S. government embargo, or that has been\n    designated by the U.S. government as a \"terrorist-supporting\" country\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service (or 16 in the European Union and United Kingdom).\n"
source_yaml_url: https://artifacts.apis.io/deepinquiry/eligibility/deepinquiry-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from DeepInquiry Verified Facts API (Machine Accountability Corp)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Facts
- Verification
- Data
---
