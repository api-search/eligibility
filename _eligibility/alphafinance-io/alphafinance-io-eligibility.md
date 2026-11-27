---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: It is published from Australia and is not directed at anyone in a place where publishing or reading it would be against the law.
  entity_types:
  - text: One account is for one person.
    type: individual
  minimum_age:
    text: The site is written for adults. If you are under 18, please do not use it.
    value: '18'
  restricted_uses:
  - summary: Products restricted in some countries
    text: Some products that appear in the data, such as leveraged derivatives, prediction markets and tokenised stocks, are restricted or not offered to residents of some countries, and that can include Australia.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Keep access to the email address or Google account you sign in with, because that is how the account is reached.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alpha Finance
provenance_date: '2026-11-09'
provider_name: Alpha Finance
provider_slug: alphafinance-io
slug: alphafinance-io-eligibility
source_date: '2026-11-09'
source_filename: alphafinance-io-eligibility.yml
source_heading: Eligibility
source_page: https://alphafinance.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alpha Finance\naid: alphafinance-io\nurl: https://alphafinance.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: It is published from Australia and is not directed at anyone in a place where publishing or reading it would\n    be against the law.\nentity_types:\n- type: individual\n  text: One account is for one person.\nrestricted_uses:\n- summary: Products restricted in some countries\n  text: Some products that appear in the data, such as leveraged derivatives, prediction markets and tokenised stocks,\n    are restricted or not offered to residents of some countries, and\
  \ that can include Australia.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Keep access to the email address or Google account you sign in with, because that is how the account is\n    reached.\nminimum_age:\n  value: '18'\n  text: The site is written for adults. If you are under 18, please do not use it.\n"
source_yaml_url: https://artifacts.apis.io/alphafinance-io/eligibility/alphafinance-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Alpha Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Data
- Markets
- Terminal
---
