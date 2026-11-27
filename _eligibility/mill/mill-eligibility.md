---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Products and Services are only available, and may only be used, in the contiguous United States.
  entity_types:
  - text: You must be at least 18 years of age to purchase any of our Products and Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to purchase any of our Products and Services.
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
name: Mill
provenance_date: '2026-11-10'
provider_name: Mill
provider_slug: mill
slug: mill-eligibility
source_date: '2026-11-10'
source_filename: mill-eligibility.yml
source_heading: Eligibility
source_page: https://www.mill.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mill\naid: mill\nurl: https://www.mill.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Products and Services are only available, and may only be used, in the contiguous United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to purchase any of our Products and Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to purchase any of our Products and Services.\n"
source_yaml_url: https://artifacts.apis.io/mill/eligibility/mill-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Mill's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Food Waste
- Sustainability
- Composting
- Smart Home
- Hardware
- Climate
---
