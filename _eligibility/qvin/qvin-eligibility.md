---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using the Site, you represent to us that you are over the age of 18 (or the age of majority in your jurisdiction, whichever is older)
    type: individual
  minimum_age:
    text: you are over the age of 18 (or the age of majority in your jurisdiction, whichever is older)
    value: '18'
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
name: Qvin
provenance_date: '2026-11-10'
provider_name: Qvin
provider_slug: qvin
slug: qvin-eligibility
source_date: '2026-11-10'
source_filename: qvin-eligibility.yml
source_heading: Eligibility
source_page: https://qvin.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qvin\naid: qvin\nurl: https://qvin.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By accessing or using the Site, you represent to us that you are over the age of 18 (or the age of majority\n    in your jurisdiction, whichever is older)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are over the age of 18 (or the age of majority in your jurisdiction, whichever is older)\n"
source_yaml_url: https://artifacts.apis.io/qvin/eligibility/qvin-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Qvin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Diagnostics
- Women's Health
- Medical Devices
- Laboratory
- Biomarkers
---
