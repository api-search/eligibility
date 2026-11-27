---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: in case the Client is a physical person, (i) it is a citizen of Azerbaijan Republic or holds permanent stay permit in this country and (ii) it is over 18 years old
    type: individual
  - text: the account number it has presented for Payments is a business account
    type: business
  minimum_age:
    text: it is over 18 years old
    value: '18'
  restricted_uses:
  - summary: Anti-corruption restrictions
    text: use the financial means obtained from our Services for the purpose of funding payments to any officer or employee of a governmental authority
  - summary: Terrorism and sanctions restrictions
    text: or in any sanctioned country or in any manner that would result in the violation of any sanctions applicable to any Party thereto
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
name: Epoint
provenance_date: '2026-11-09'
provider_name: Epoint
provider_slug: epoint
slug: epoint-eligibility
source_date: '2026-11-09'
source_filename: epoint-eligibility.yml
source_heading: Eligibility
source_page: https://epoint.az/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Epoint\naid: epoint\nurl: https://epoint.az/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: in case the Client is a physical person, (i) it is a citizen of Azerbaijan Republic or holds permanent stay\n    permit in this country and (ii) it is over 18 years old\n- type: business\n  text: the account number it has presented for Payments is a business account\nrestricted_uses:\n- summary: Anti-corruption restrictions\n  text: use the financial means obtained from our Services for the purpose of funding payments to any officer\
  \ or\n    employee of a governmental authority\n- summary: Terrorism and sanctions restrictions\n  text: or in any sanctioned country or in any manner that would result in the violation of any sanctions applicable\n    to any Party thereto\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: it is over 18 years old\n"
source_yaml_url: https://artifacts.apis.io/epoint/eligibility/epoint-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Epoint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Payment Gateway
- Fintech
- E-Commerce
- Card Payments
- Azerbaijan
- Apple Pay
- Google Pay
- Digital Wallet
---
