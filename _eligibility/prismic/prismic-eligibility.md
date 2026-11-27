---
api_specs:
- filename: TzCHBqbH
  format: yaml
  label: Prismic Types API
  slug: types-api
  spec_type: Postman
  url: https://documenter.getpostman.com/view/5743666/TzCHBqbH
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: you shall not permit any access or use of the Solution in a United States embargoed country (currently Cuba, Iran, North Korea, Sudan or Syria).
  minimum_age:
    text: YOU MUST BE 18 YEARS OF AGE OR OLDER TO CREATE AND ACCOUNT AND ACCESS THE SOLUTION.
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: Prismic may in its sole discretion determine whether your use of the Solutions is a violation of this AUP
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prismic
provenance_date: '2026-11-10'
provider_name: Prismic
provider_slug: prismic
slug: prismic-eligibility
source_date: '2026-11-10'
source_filename: prismic-eligibility.yml
source_heading: Eligibility
source_page: https://prismic.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prismic\naid: prismic\nurl: https://prismic.io/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: you shall not permit any access or use of the Solution in a United States embargoed country (currently Cuba,\n    Iran, North Korea, Sudan or Syria).\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Prismic may in its sole discretion determine whether your use of the Solutions is a violation of this AUP\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: YOU MUST BE 18 YEARS OF AGE OR OLDER TO CREATE AND ACCOUNT AND ACCESS THE SOLUTION.\n"
source_yaml_url: https://artifacts.apis.io/prismic/eligibility/prismic-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Prismic's own page on 2026-11-10.
synthetic: false
tags:
- GraphQL
- Headless CMS
- Content Management
- Page Builder
- JAMstack
- Marketing
- Content Delivery
- Developer Tools
- MCP
- Webhook
- Localization
- Digital Asset Management
---
