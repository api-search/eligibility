---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We may offer different pricing in different geographic regions.
  minimum_age:
    text: If you are from the European Economic Area (EEA) and under the age of 16, you must provide us with a parental consent.
    value: null
  restricted_uses:
  - summary: Regional pricing circumvention
    text: purchase or attempt to purchase subscriptions to the Service from locations outside your declared country of residence for the purpose of taking advantage of regional pricing differences
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
name: Anghami
provenance_date: '2026-11-09'
provider_name: Anghami
provider_slug: anghami
slug: anghami-eligibility
source_date: '2026-11-09'
source_filename: anghami-eligibility.yml
source_heading: Eligibility
source_page: https://www.anghami.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anghami\naid: anghami\nurl: https://www.anghami.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We may offer different pricing in different geographic regions.\nentity_types: []\nrestricted_uses:\n- summary: Regional pricing circumvention\n  text: purchase or attempt to purchase subscriptions to the Service from locations outside your declared country\n    of residence for the purpose of taking advantage of regional pricing differences\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you are from\
  \ the European Economic Area (EEA) and under the age of 16, you must provide us with a parental\n    consent.\n"
source_yaml_url: https://artifacts.apis.io/anghami/eligibility/anghami-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Anghami's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Streaming
- Middle East
- North-Africa
- Entertainment
---
