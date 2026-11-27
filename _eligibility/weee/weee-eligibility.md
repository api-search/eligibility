---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory or other jurisdiction that is embargoed by the United States
  entity_types:
  - text: You must be at least 18 years of age (or the age of legal majority where you live) to create an account or make purchases through our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the age of legal majority where you live) to create an account or make purchases through our Services.
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
name: Weee
provenance_date: '2026-11-10'
provider_name: Weee
provider_slug: weee
slug: weee-eligibility
source_date: '2026-11-10'
source_filename: weee-eligibility.yml
source_heading: Eligibility
source_page: https://www.weee.com/en/about/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Weee\naid: weee\nurl: https://www.weee.com/en/about/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory\n    or other jurisdiction that is embargoed by the United States\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age (or the age of legal majority where you live) to create an account\n    or make purchases through our Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of legal majority where you live) to create an account\n    or make purchases through our Services.\n"
source_yaml_url: https://artifacts.apis.io/weee/eligibility/weee-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Weee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Grocery
- E-Commerce
- Food and Beverage
- Delivery
- Retail
- Marketplace
- Asian Groceries
---
