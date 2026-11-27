---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services are not directed to children under 13 (or other age as required by local law)
    value: '13'
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
name: Convene
provenance_date: '2026-11-09'
provider_name: Convene
provider_slug: convene
slug: convene-eligibility
source_date: '2026-11-09'
source_filename: convene-eligibility.yml
source_heading: Eligibility
source_page: https://convene.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Convene\naid: convene\nurl: https://convene.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are not directed to children under 13 (or other age as required by local law)\n"
source_yaml_url: https://artifacts.apis.io/convene/eligibility/convene-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Convene's own page on 2026-11-09.
synthetic: false
tags:
- Meetings
- Event
- Flexible Office
- Workplace
- Hospitality
- Technology
---
