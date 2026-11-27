---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Corporate Website is intended for an audience 21 years of age or older.
    type: individual
  minimum_age:
    text: This Corporate Website is intended for an audience 21 years of age or older.
    value: '21'
  restricted_uses:
  - summary: Illegal or abusive submissions
    text: You agree that you will not transmit content to JUUL Labs that is illegal, obscene, threatening, defamatory, invasive of privacy, infringing of intellectual property rights, or otherwise injurious to third parties
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
name: JUUL
provenance_date: '2026-11-09'
provider_name: JUUL
provider_slug: juul
slug: juul-eligibility
source_date: '2026-11-09'
source_filename: juul-eligibility.yml
source_heading: Eligibility
source_page: https://www.juullabs.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JUUL\naid: juul\nurl: https://www.juullabs.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Corporate Website is intended for an audience 21 years of age or older.\nrestricted_uses:\n- summary: Illegal or abusive submissions\n  text: You agree that you will not transmit content to JUUL Labs that is illegal, obscene, threatening, defamatory,\n    invasive of privacy, infringing of intellectual property rights, or otherwise injurious to third parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '21'\n  text: This Corporate Website is intended for an audience 21 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/juul/eligibility/juul-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from JUUL's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Products
- Nicotine
- Vaping
- Hardware
- Consumer Electronics
- Bluetooth Low Energy
- Open Source
- Kotlin Multiplatform
- Regulated Industry
---
