---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: на территории всех стран мира
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with local law
    text: Пользователь обязуется использовать Сервис в соответствии с законами той страны, в которой он находится
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
name: Aviasales
provenance_date: '2026-11-09'
provider_name: Aviasales
provider_slug: aviasales
slug: aviasales-eligibility
source_date: '2026-11-09'
source_filename: aviasales-eligibility.yml
source_heading: Eligibility
source_page: https://www.aviasales.ru/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aviasales\naid: aviasales\nurl: https://www.aviasales.ru/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: на территории всех стран мира\nentity_types: []\nrestricted_uses:\n- summary: Compliance with local law\n  text: Пользователь обязуется использовать Сервис в соответствии с законами той страны, в которой он находится\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aviasales/eligibility/aviasales-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Aviasales's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Flights
- Booking
- Russia
---
