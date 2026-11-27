---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Klient/Uczestnik - osoba, która jest już zarejestrowana w aplikacji mobilnej/ Serwisie Pstryk
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Same-person referral pairs
    text: Polecenie dokonane pomiędzy dwoma kontami należącymi do tej samej osoby, nie rodzi prawa do przyznania środków w ramach Programu.
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
name: Pstryk
provenance_date: '2026-11-10'
provider_name: Pstryk
provider_slug: pstryk
slug: pstryk-eligibility
source_date: '2026-11-10'
source_filename: pstryk-eligibility.yml
source_heading: Eligibility
source_page: https://pstryk.pl/regulamin-pstryk-polecaj
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pstryk\naid: pstryk\nurl: https://pstryk.pl/regulamin-pstryk-polecaj\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Klient/Uczestnik - osoba, która jest już zarejestrowana w aplikacji mobilnej/ Serwisie Pstryk\nrestricted_uses:\n- summary: Same-person referral pairs\n  text: Polecenie dokonane pomiędzy dwoma kontami należącymi do tej samej osoby, nie rodzi prawa do przyznania środków\n    w ramach Programu.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pstryk/eligibility/pstryk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Pstryk's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Utilities
- Fintech
- Poland
- Dynamic Pricing
---
