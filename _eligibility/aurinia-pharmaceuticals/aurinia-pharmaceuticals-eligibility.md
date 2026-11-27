---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You represent, warrant and covenant that: (i) you have the power and authority to enter into this Agreement; (ii) you are at least 18 years of age'
    type: individual
  minimum_age:
    text: you are at least 18 years of age
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
name: Aurinia Pharmaceuticals
provenance_date: '2026-11-09'
provider_name: Aurinia Pharmaceuticals
provider_slug: aurinia-pharmaceuticals
slug: aurinia-pharmaceuticals-eligibility
source_date: '2026-11-09'
source_filename: aurinia-pharmaceuticals-eligibility.yml
source_heading: Eligibility
source_page: https://www.auriniapharma.com/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aurinia Pharmaceuticals\naid: aurinia-pharmaceuticals\nurl: https://www.auriniapharma.com/policies/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You represent, warrant and covenant that: (i) you have the power and authority to enter into this Agreement;\n    (ii) you are at least 18 years of age'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/aurinia-pharmaceuticals/eligibility/aurinia-pharmaceuticals-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Aurinia Pharmaceuticals's own page on 2026-11-09.
synthetic: false
tags:
- Biopharma
- Autoimmune
- Therapeutics
- Clinical Research
- Biotechnology
---
