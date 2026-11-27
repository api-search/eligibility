---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unsere Services richten sich ausschließlich an Verbraucher. Für Zwecke dieser Nutzungsbedingungen ist ein Verbraucher jede natürliche Person
    type: individual
  minimum_age:
    text: mindestens 16 Jahre alt sind
    value: '16'
  restricted_uses:
  - summary: Some deals age-restricted
    text: Hiervon abweichend ist die Teilnahme an einzelnen Cashback-Deals oder Sammelpass-Deals erst ab dem vollendeten 18. Lebensjahr möglich.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Auf Anforderung von acardo sind Sie außerdem verpflichtet, die Korrektheit dieser Angaben nachzuweisen.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scondoo
provenance_date: '2026-11-10'
provider_name: Scondoo
provider_slug: scondoo
slug: scondoo-eligibility
source_date: '2026-11-10'
source_filename: scondoo-eligibility.yml
source_heading: Eligibility
source_page: https://scondoo.de/nutzungsbedingungen
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scondoo\naid: scondoo\nurl: https://scondoo.de/nutzungsbedingungen\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Unsere Services richten sich ausschließlich an Verbraucher. Für Zwecke dieser Nutzungsbedingungen ist ein\n    Verbraucher jede natürliche Person\nrestricted_uses:\n- summary: Some deals age-restricted\n  text: Hiervon abweichend ist die Teilnahme an einzelnen Cashback-Deals oder Sammelpass-Deals erst ab dem vollendeten\n    18. Lebensjahr möglich.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: Auf Anforderung von acardo sind Sie außerdem verpflichtet, die Korrektheit dieser Angaben nachzuweisen.\nminimum_age:\n  value: '16'\n  text: mindestens 16 Jahre alt sind\n"
source_yaml_url: https://artifacts.apis.io/scondoo/eligibility/scondoo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Scondoo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cashback
- Coupons
- Retail
- Consumer
- Mobile App
- Germany
- Shopping
---
