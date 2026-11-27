---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be a U.S. citizen or legal permanent resident of the United States of at least eighteen 18 years of age, or the age of majority in your state, whichever is older, to use the Sites
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: you are hereby granted a non-exclusive, limited, non-transferable, freely revocable license to use the Sites for your personal, noncommercial use only
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: When you open an account, we will ask for your name, address, date of birth, and other information that will allow us to identify you.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cardless
provenance_date: '2026-11-09'
provider_name: Cardless
provider_slug: cardless
slug: cardless-eligibility
source_date: '2026-11-09'
source_filename: cardless-eligibility.yml
source_heading: Eligibility
source_page: https://legal.cardless.com/terms_of_service/default/terms_of_service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cardless\naid: cardless\nurl: https://legal.cardless.com/terms_of_service/default/terms_of_service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be a U.S. citizen or legal permanent resident of the United States of at least eighteen 18 years\n    of age, or the age of majority in your state, whichever is older, to use the Sites\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: you are hereby granted a non-exclusive, limited, non-transferable, freely revocable license to use the Sites\n    for your personal, noncommercial\
  \ use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: When you open an account, we will ask for your name, address, date of birth, and other information that\n    will allow us to identify you.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cardless/eligibility/cardless-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Cardless's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Credit Cards
- Card Issuing
- Embedded Finance
- Payments
- Banking as a Service
- Lending
- Co-Branded Cards
- Loyalty
---
