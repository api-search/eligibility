---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Nidra is intended for prescription use only and is only available for commercial sale in the United States by or on the order of a physician.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prescription device sale restriction
    text: 'Caution: Federal law restricts this device to sale by or on the order of a medical professional.'
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
name: Noctrix Health
provenance_date: '2026-11-10'
provider_name: Noctrix Health
provider_slug: noctrix-health
slug: noctrix-health-eligibility
source_date: '2026-11-10'
source_filename: noctrix-health-eligibility.yml
source_heading: Eligibility
source_page: https://nidrarls.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Noctrix Health\naid: noctrix-health\nurl: https://nidrarls.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Nidra is intended for prescription use only and is only available for commercial sale in the United States\n    by or on the order of a physician.\nentity_types: []\nrestricted_uses:\n- summary: Prescription device sale restriction\n  text: 'Caution: Federal law restricts this device to sale by or on the order of a medical professional.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/noctrix-health/eligibility/noctrix-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Noctrix Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Medical Devices
- Digital Health
- Sleep
- Neurology
- Neurostimulation
- Wearables
- MCP
- Agent Readiness
---
