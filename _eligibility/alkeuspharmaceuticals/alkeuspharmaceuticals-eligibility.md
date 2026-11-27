---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Product information contained in the Website is intended for residents of the U.S., unless otherwise specified.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical advice via website
    text: ALKEUS IS NOT ENGAGED IN RENDERING MEDICAL OR SIMILAR PROFESSIONAL SERVICES OR ADVICE VIA THE WEBSITE
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
name: Alkeuspharmaceuticals
provenance_date: '2026-11-09'
provider_name: Alkeuspharmaceuticals
provider_slug: alkeuspharmaceuticals
slug: alkeuspharmaceuticals-eligibility
source_date: '2026-11-09'
source_filename: alkeuspharmaceuticals-eligibility.yml
source_heading: Eligibility
source_page: https://alkeuspharma.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alkeuspharmaceuticals\naid: alkeuspharmaceuticals\nurl: https://alkeuspharma.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Product information contained in the Website is intended for residents of the U.S., unless otherwise specified.\nentity_types: []\nrestricted_uses:\n- summary: No medical advice via website\n  text: ALKEUS IS NOT ENGAGED IN RENDERING MEDICAL OR SIMILAR PROFESSIONAL SERVICES OR ADVICE VIA THE WEBSITE\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alkeuspharmaceuticals/eligibility/alkeuspharmaceuticals-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Alkeuspharmaceuticals's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Pharmaceuticals
- Retinal Disease
- Clinical Trials
- VisionHealth
---
