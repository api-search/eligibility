---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'You represent and warrant that you are: ... (c) a resident of the United States'
  minimum_age:
    text: 'You represent and warrant that you are: (a) over eighteen years of age or the age of majority in our jurisdiction, whichever is greater'
    value: '18'
  restricted_uses:
  - summary: Personal-use only
    text: may only be exercised for your personal use
  - summary: Non-competing use
    text: not a person who markets, sells or distributes or works, directly or indirectly, for any entity that markets, sells or distributes any products or services that compete with those offered by Rabbet
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
name: Rabbet
provenance_date: '2026-11-10'
provider_name: Rabbet
provider_slug: rabbet
slug: rabbet-eligibility
source_date: '2026-11-10'
source_filename: rabbet-eligibility.yml
source_heading: Eligibility
source_page: https://rabbet.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rabbet\naid: rabbet\nurl: https://rabbet.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'You represent and warrant that you are: ... (c) a resident of the United States'\nentity_types: []\nrestricted_uses:\n- summary: Personal-use only\n  text: may only be exercised for your personal use\n- summary: Non-competing use\n  text: not a person who markets, sells or distributes or works, directly or indirectly, for any entity that markets,\n    sells or distributes any products or services that compete with those offered by Rabbet\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'You represent and warrant that you are: (a) over eighteen years of age or the age of majority in our jurisdiction,\n    whichever is greater'\n"
source_yaml_url: https://artifacts.apis.io/rabbet/eligibility/rabbet-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Rabbet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Construction Finance
- Construction Lending
- Real Estate
- Draw Management
- Loan Origination
- Payments
---
