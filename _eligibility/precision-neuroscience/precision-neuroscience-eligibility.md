---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are accessing and using the Website or Content from the United States
  entity_types:
  - text: (a) you are older than 18 years of age
    type: individual
  minimum_age:
    text: (a) you are older than 18 years of age
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
name: Precision Neuroscience
provenance_date: '2026-11-10'
provider_name: Precision Neuroscience
provider_slug: precision-neuroscience
slug: precision-neuroscience-eligibility
source_date: '2026-11-10'
source_filename: precision-neuroscience-eligibility.yml
source_heading: Eligibility
source_page: https://www.precisionneuro.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Precision Neuroscience\naid: precision-neuroscience\nurl: https://www.precisionneuro.io/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are accessing and using the Website or Content from the United States\nentity_types:\n- type: individual\n  text: (a) you are older than 18 years of age\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (a) you are older than 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/precision-neuroscience/eligibility/precision-neuroscience-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Precision Neuroscience's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Brain-Computer Interface
- Neurotechnology
- Medical Devices
- Neuroscience
- Implantable Devices
- neural-interfaces
- Health Tech
- Clinical Research
- Deep Tech
---
