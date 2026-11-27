---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You agree not to attempt to access the Services from any country under sanctions by the Office of Foreign Asset Control ("OFAC").
  entity_types:
  - text: The Services are intended for use by individuals who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Services are intended for use by individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No unauthorized or illegal use
    text: Any unauthorized or illegal use of the Services is strictly prohibited.
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
name: Possible Finance
provenance_date: '2026-11-10'
provider_name: Possible Finance
provider_slug: possible-finance
slug: possible-finance-eligibility
source_date: '2026-11-10'
source_filename: possible-finance-eligibility.yml
source_heading: Eligibility
source_page: https://www.possiblefinance.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Possible Finance\naid: possible-finance\nurl: https://www.possiblefinance.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You agree not to attempt to access the Services from any country under sanctions by the Office of Foreign\n    Asset Control (\"OFAC\").\nentity_types:\n- type: individual\n  text: The Services are intended for use by individuals who are at least 18 years old.\nrestricted_uses:\n- summary: No unauthorized or illegal use\n  text: Any unauthorized or illegal use of the Services is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for use by individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/possible-finance/eligibility/possible-finance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Possible Finance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Consumer Lending
- Credit Building
- Personal Finance
- Mobile App
- Financial Services
- Public Benefit Corporation
---
