---
api_specs:
- filename: kangaroo-rewards-core-api-openapi.yml
  format: yaml
  label: Kangaroo Rewards Core API
  slug: kangaroo-rewards-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kangaroo-rewards/openapi/kangaroo-rewards-core-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    - US
    text: KANGAROO and its licensors make no representation that the Service is appropriate or available for use in locations other than Canada and the United States of America.
  entity_types:
  - text: You may use the Service only for your own lawful business purposes
    type: business
  - text: You must be at least 13 years old (or the minimum legal age in your jurisdiction) to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years old (or the minimum legal age in your jurisdiction) to use the Service.
    value: '13'
  restricted_uses:
  - summary: Competitors barred from access
    text: You may not access the Service if you or any of your Affiliates is/are a direct competitor of KANGAROO
  - summary: Illegal purposes
    text: Use the Service for any illegal purpose.
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
name: Kangaroo Rewards
provenance_date: '2026-11-09'
provider_name: Kangaroo Rewards
provider_slug: kangaroo-rewards
slug: kangaroo-rewards-eligibility
source_date: '2026-11-09'
source_filename: kangaroo-rewards-eligibility.yml
source_heading: Eligibility
source_page: https://loyalty.kangaroorewards.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kangaroo Rewards\naid: kangaroo-rewards\nurl: https://loyalty.kangaroorewards.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  - US\n  excluded: []\n  text: KANGAROO and its licensors make no representation that the Service is appropriate or available for use in\n    locations other than Canada and the United States of America.\nentity_types:\n- type: business\n  text: You may use the Service only for your own lawful business purposes\n- type: individual\n  text: You must be at least 13 years old (or the minimum legal age in your jurisdiction) to use the Service.\nrestricted_uses:\n\
  - summary: Competitors barred from access\n  text: You may not access the Service if you or any of your Affiliates is/are a direct competitor of KANGAROO\n- summary: Illegal purposes\n  text: Use the Service for any illegal purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or the minimum legal age in your jurisdiction) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/kangaroo-rewards/eligibility/kangaroo-rewards-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Kangaroo Rewards's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Loyalty
- Marketing
- Software-as-a-Service
- Rewards
---
