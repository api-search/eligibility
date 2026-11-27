---
api_specs:
- filename: avnester-com-public-api-openapi.yml
  format: yaml
  label: AVnester Public API
  slug: avnester-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avnester-com/openapi/avnester-com-public-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Indian real estate platform; operated by a company incorporated in India.
  entity_types:
  - text: You must be at least 18 years old and competent to contract under the Indian Contract Act, 1872.
    type: individual
  - text: If you act for an organisation, you confirm you are authorised to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and competent to contract under the Indian Contract Act, 1872.
    value: '18'
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
name: AVnester
provenance_date: '2026-11-09'
provider_name: AVnester
provider_slug: avnester-com
slug: avnester-com-eligibility
source_date: '2026-11-09'
source_filename: avnester-com-eligibility.yml
source_heading: Eligibility
source_page: https://avnester.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AVnester\naid: avnester-com\nurl: https://avnester.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Indian real estate platform; operated by a company incorporated in India.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and competent to contract under the Indian Contract Act, 1872.\n- type: business\n  text: If you act for an organisation, you confirm you are authorised to bind it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at\
  \ least 18 years old and competent to contract under the Indian Contract Act, 1872.\n"
source_yaml_url: https://artifacts.apis.io/avnester-com/eligibility/avnester-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from AVnester's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Artificial Intelligence
- Property Listings
- India
- Marketplace
---
