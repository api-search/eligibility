---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: No medical advice or emergency use
    text: THE SERVICES SHOULD NEVER BE USED AS A SUBSTITUTE FOR EMERGENCY CARE.
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
name: Genalyte
provenance_date: '2026-11-09'
provider_name: Genalyte
provider_slug: genalyte
slug: genalyte-eligibility
source_date: '2026-11-09'
source_filename: genalyte-eligibility.yml
source_heading: Eligibility
source_page: https://www.genalyte.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Genalyte\naid: genalyte\nurl: https://www.genalyte.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission\nrestricted_uses:\n- summary: No medical advice or emergency use\n  text: THE SERVICES SHOULD NEVER BE USED AS A SUBSTITUTE FOR EMERGENCY CARE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/genalyte/eligibility/genalyte-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Genalyte's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Diagnostics
- Medical Devices
- Laboratory
- Point of Care Testing
- Life Sciences
- Biotechnology
- In Vitro Diagnostics
---
