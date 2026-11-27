---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Our Website is operated, and services are provided in compliance with the laws in India and Company shall not be liable to deliver any Products or provide any Services purchased by You in locations outside India.
  entity_types:
  - text: Use of the Website is available only to persons who can form legally binding contracts under Indian Contract Act, 1872.
    type: individual
  minimum_age:
    text: if You are below the age of eighteen (18) years, You may avail the services provided by the Website, through Your legal guardian in accordance with the applicable laws.
    value: '18'
  restricted_uses:
  - summary: Resale of purchased products or services
    text: The User hereby expressly agrees that any merchandize, or Services purchased by the User will not be sold, resold, bartered or in any way be used for any commercial purposes or for profit.
  - summary: Multiple accounts
    text: You shall not have more than one active Account on the Website.
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
name: Pharmeasy
provenance_date: '2026-11-10'
provider_name: Pharmeasy
provider_slug: pharmeasy
slug: pharmeasy-eligibility
source_date: '2026-11-10'
source_filename: pharmeasy-eligibility.yml
source_heading: Eligibility
source_page: https://pharmeasy.in/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pharmeasy\naid: pharmeasy\nurl: https://pharmeasy.in/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Our Website is operated, and services are provided in compliance with the laws in India and Company shall\n    not be liable to deliver any Products or provide any Services purchased by You in locations outside India.\nentity_types:\n- type: individual\n  text: Use of the Website is available only to persons who can form legally binding contracts under Indian Contract\n    Act, 1872.\nrestricted_uses:\n- summary: Resale of purchased\
  \ products or services\n  text: The User hereby expressly agrees that any merchandize, or Services purchased by the User will not be sold,\n    resold, bartered or in any way be used for any commercial purposes or for profit.\n- summary: Multiple accounts\n  text: You shall not have more than one active Account on the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if You are below the age of eighteen (18) years, You may avail the services provided by the Website, through\n    Your legal guardian in accordance with the applicable laws.\n"
source_yaml_url: https://artifacts.apis.io/pharmeasy/eligibility/pharmeasy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pharmeasy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- E-Pharmacy
- Diagnostics
- Telehealth
- India
- E-Commerce
---
