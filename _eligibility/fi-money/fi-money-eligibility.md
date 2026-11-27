---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Participation is open only to natural persons who are residents of India, 18 years or older on the date of entry, and who hold a valid Instagram account.
  entity_types:
  - text: Please note that the limit mentioned above is only for resident individuals
    type: individual
  - text: is not available to corporates, partnership firms, HUFs, Trusts etc.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Tamil Nadu rewards restriction
    text: users of our Platform residing in the State of Tamil Nadu are not eligible to participate in specific rewards/offers
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To fulfil such KYC requirements, Epifi procures personal identification details from you before any Services can be delivered
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fi Money
provenance_date: '2026-11-09'
provider_name: Fi Money
provider_slug: fi-money
slug: fi-money-eligibility
source_date: '2026-11-09'
source_filename: fi-money-eligibility.yml
source_heading: Eligibility
source_page: https://fi.money/blog/tnc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fi Money\naid: fi-money\nurl: https://fi.money/blog/tnc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Participation is open only to natural persons who are residents of India, 18 years or older on the date\n    of entry, and who hold a valid Instagram account.\nentity_types:\n- type: individual\n  text: Please note that the limit mentioned above is only for resident individuals\n- type: business\n  text: is not available to corporates, partnership firms, HUFs, Trusts etc.\nrestricted_uses:\n- summary: Tamil Nadu rewards restriction\n  text: users of our Platform residing in the\
  \ State of Tamil Nadu are not eligible to participate in specific rewards/offers\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To fulfil such KYC requirements, Epifi procures personal identification details from you before any Services\n    can be delivered\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fi-money/eligibility/fi-money-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Fi Money's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Neobank
- Consumer Banking
- Personal Finance
- Money Management
- Wealth Analyzer
- Mutual Funds
- Stocks
- EPF
- Credit Cards
- Personal Loans
- Savings
- UPI
- India
- Federal Bank
- MCP
- AI Assistant
- Mobile Banking
---
