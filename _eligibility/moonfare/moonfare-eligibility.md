---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: permits qualified individuals to invest in private equity funds via the Platform.
    type: individual
  - text: (b) the entity on whose behalf you are accessing and using the Platform and Services
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
name: Moonfare
provenance_date: '2026-11-10'
provider_name: Moonfare
provider_slug: moonfare
slug: moonfare-eligibility
source_date: '2026-11-10'
source_filename: moonfare-eligibility.yml
source_heading: Eligibility
source_page: https://www.moonfare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moonfare\naid: moonfare\nurl: https://www.moonfare.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: permits qualified individuals to invest in private equity funds via the Platform.\n- type: business\n  text: (b) the entity on whose behalf you are accessing and using the Platform and Services\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moonfare/eligibility/moonfare-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Moonfare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Private Equity
- Venture Capital
- Fintech
- Investing
- Wealth Management
- Alternative Investments
- Financial Services
---
