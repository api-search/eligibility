---
api_specs:
- filename: boston-properties-wp-json-discovery.json
  format: json
  label: Boston Properties (BXP) Website (WordPress REST)
  slug: bxp-com-website-wordpress-rest
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boston-properties/openapi/boston-properties-wp-json-discovery.json
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These pages are controlled and operated by BXP in the United States and are intended for use within the United States. BXP makes no representation that materials on these pages are appropriate or available for use in other locations.
  minimum_age:
    text: null
    value: null
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
name: Boston Properties (BXP)
provenance_date: '2026-11-09'
provider_name: Boston Properties (BXP)
provider_slug: boston-properties
slug: boston-properties-eligibility
source_date: '2026-11-09'
source_filename: boston-properties-eligibility.yml
source_heading: Eligibility
source_page: https://www.bxp.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boston Properties (BXP)\naid: boston-properties\nurl: https://www.bxp.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These pages are controlled and operated by BXP in the United States and are intended for use within the\n    United States. BXP makes no representation that materials on these pages are appropriate or available for use\n    in other locations.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boston-properties/eligibility/boston-properties-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Boston Properties (BXP)'s own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Commercial Real Estate
- REIT
- Office Properties
- Workplace
- Fortune 1000
---
