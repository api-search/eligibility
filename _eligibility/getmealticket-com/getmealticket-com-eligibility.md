---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We may block access to certain Services (or certain service features or content) in certain countries.
  entity_types:
  - text: The Site and App are available only to individuals who (a) are at least eighteen (18) years old
    type: individual
  - text: business Users, such as restaurants and food providers, may open several accounts for the purpose of integrating them together and to be used by their employees.
    type: business
  minimum_age:
    text: The Site and App are available only to individuals who (a) are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: use the Site and/or App and/or the Content and/or User Generated Content for any illegal, immoral, unlawful and/or unauthorized purposes
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
name: Meal Ticket
provenance_date: '2026-11-09'
provider_name: Meal Ticket
provider_slug: getmealticket-com
slug: getmealticket-com-eligibility
source_date: '2026-11-09'
source_filename: getmealticket-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.mealticket.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meal Ticket\naid: getmealticket-com\nurl: https://www.mealticket.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We may block access to certain Services (or certain service features or content) in certain countries.\nentity_types:\n- type: individual\n  text: The Site and App are available only to individuals who (a) are at least eighteen (18) years old\n- type: business\n  text: business Users, such as restaurants and food providers, may open several accounts for the purpose of integrating\n    them together and to be used by their employees.\nrestricted_uses:\n\
  - summary: Illegal or unauthorized purposes\n  text: use the Site and/or App and/or the Content and/or User Generated Content for any illegal, immoral, unlawful\n    and/or unauthorized purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and App are available only to individuals who (a) are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/getmealticket-com/eligibility/getmealticket-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Meal Ticket's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Service
- Profitability
- Software-as-a-Service
- B2B
---
