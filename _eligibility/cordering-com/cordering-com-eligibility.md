---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - RS
    text: Goods and services from the Partner's Offering are sold and delivered exclusively within the territory of the Republic of Serbia.
  entity_types:
  - text: a B2B digital platform intended for business entities in the hospitality and food industry (Partners), as well as business users who order meals for their employees
    type: business
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
name: COrdering
provenance_date: '2026-11-09'
provider_name: COrdering
provider_slug: cordering-com
slug: cordering-com-eligibility
source_date: '2026-11-09'
source_filename: cordering-com-eligibility.yml
source_heading: Eligibility
source_page: https://cordering.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: COrdering\naid: cordering-com\nurl: https://cordering.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - RS\n  excluded: []\n  text: Goods and services from the Partner's Offering are sold and delivered exclusively within the territory of\n    the Republic of Serbia.\nentity_types:\n- type: business\n  text: a B2B digital platform intended for business entities in the hospitality and food industry (Partners), as\n    well as business users who order meals for their employees\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cordering-com/eligibility/cordering-com-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from COrdering's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Ordering
- Restaurants
- Catering
- Corporate Meals
- Food Delivery
- Mobile Apps
- MCP
- Serbia
---
