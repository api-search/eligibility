---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not available in all states.
  entity_types:
  - text: The Site and Services are intended only for those who are 18 years of age or older (or the age of majority in your jurisdiction, if it is above 18).
    type: individual
  minimum_age:
    text: The Site and Services are intended only for those who are 18 years of age or older (or the age of majority in your jurisdiction, if it is above 18).
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties or countries
    text: you are not located in any country that is subject to United States country-wide sanctions or that has been designated by the United States as a "terrorist supporting" country
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
name: Milo Credit
provenance_date: '2026-11-10'
provider_name: Milo Credit
provider_slug: milo-credit
slug: milo-credit-eligibility
source_date: '2026-11-10'
source_filename: milo-credit-eligibility.yml
source_heading: Eligibility
source_page: https://www.milo.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Milo Credit\naid: milo-credit\nurl: https://www.milo.io/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not available in all states.\nentity_types:\n- type: individual\n  text: The Site and Services are intended only for those who are 18 years of age or older (or the age of majority\n    in your jurisdiction, if it is above 18).\nrestricted_uses:\n- summary: Sanctioned parties or countries\n  text: you are not located in any country that is subject to United States country-wide sanctions or that has been\n    designated by the United States as a \"terrorist supporting\"\
  \ country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and Services are intended only for those who are 18 years of age or older (or the age of majority\n    in your jurisdiction, if it is above 18).\n"
source_yaml_url: https://artifacts.apis.io/milo-credit/eligibility/milo-credit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Milo Credit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Mortgage
- Cryptocurrency
- Crypto-Backed Loans
- Real Estate
- Consumer Finance
---
