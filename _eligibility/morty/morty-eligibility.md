---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This website provides information regarding services and products that are made available in the United States only.
  minimum_age:
    text: You will only access or use this website and transact business with us if you are at least 18 years old;
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: You will not use the Site or Service for any illegal purpose.
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
name: Morty
provenance_date: '2026-11-10'
provider_name: Morty
provider_slug: morty
slug: morty-eligibility
source_date: '2026-11-10'
source_filename: morty-eligibility.yml
source_heading: Eligibility
source_page: https://www.morty.com/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Morty\naid: morty\nurl: https://www.morty.com/legal/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This website provides information regarding services and products that are made available in the United\n    States only.\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: You will not use the Site or Service for any illegal purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You will only access or use this website and transact business with us if you are at least 18 years\
  \ old;\n"
source_yaml_url: https://artifacts.apis.io/morty/eligibility/morty-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Morty's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mortgage
- Lending
- Fintech
- Mortgage Infrastructure
- Loan Origination
- Pricing Engine
- Embedded Finance
---
