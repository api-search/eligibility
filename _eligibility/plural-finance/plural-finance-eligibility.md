---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: nonexclusive, non-transferable license to use the Site solely for your personal use.
    type: individual
  - text: If you are accessing this site on behalf of your employer, you represent you have authority to bind your employer to these terms and conditions.
    type: business
  minimum_age:
    text: you are of legal age to contract in your jurisdiction
    value: null
  restricted_uses:
  - summary: Export and import restrictions
    text: will not export or import any Site content to any country to which export or import is restricted under United States law
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
name: Plural Finance
provenance_date: '2026-11-10'
provider_name: Plural Finance
provider_slug: plural-finance
slug: plural-finance-eligibility
source_date: '2026-11-10'
source_filename: plural-finance-eligibility.yml
source_heading: Eligibility
source_page: https://www.pluralfinance.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plural Finance\naid: plural-finance\nurl: https://www.pluralfinance.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: nonexclusive, non-transferable license to use the Site solely for your personal use.\n- type: business\n  text: If you are accessing this site on behalf of your employer, you represent you have authority to bind your\n    employer to these terms and conditions.\nrestricted_uses:\n- summary: Export and import restrictions\n  text: will not export or import any Site content to any country to which\
  \ export or import is restricted under\n    United States law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to contract in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/plural-finance/eligibility/plural-finance-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Plural Finance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Crypto Defi
- Tokenization
- Infrastructure
- Energy
- Real World Assets
- Financial Operating System
---
