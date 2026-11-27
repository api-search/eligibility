---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for clinical or diagnostic use
    text: It is not FDA approved or CE marked and not intended for any clinical or diagnostic use or use on patients or with patient data.
  - summary: Not for HIPAA/FISMA-regulated use
    text: if your interactions would be subjected to such laws, you may not use this Application.
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
name: ThinkSono
provenance_date: '2026-11-10'
provider_name: ThinkSono
provider_slug: thinksono
slug: thinksono-eligibility
source_date: '2026-11-10'
source_filename: thinksono-eligibility.yml
source_heading: Eligibility
source_page: https://thinksono.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ThinkSono\naid: thinksono\nurl: https://thinksono.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for clinical or diagnostic use\n  text: It is not FDA approved or CE marked and not intended for any clinical or diagnostic use or use on patients\n    or with patient data.\n- summary: Not for HIPAA/FISMA-regulated use\n  text: if your interactions would be subjected to such laws, you may not use this Application.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thinksono/eligibility/thinksono-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from ThinkSono's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Devices
- Artificial Intelligence
- Ultrasound
- Diagnostics
- Medical Technology
- Digital Health
---
