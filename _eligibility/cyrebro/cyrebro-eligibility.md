---
claim_count: 1
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
  - summary: No use violating law
    text: it will not use the Services in violation of applicable law, rule or regulation;
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
name: Cyrebro
provenance_date: '2026-11-09'
provider_name: Cyrebro
provider_slug: cyrebro
slug: cyrebro-eligibility
source_date: '2026-11-09'
source_filename: cyrebro-eligibility.yml
source_heading: Eligibility
source_page: https://www.cyrebro.io/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cyrebro\naid: cyrebro\nurl: https://www.cyrebro.io/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No use violating law\n  text: it will not use the Services in violation of applicable law, rule or regulation;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cyrebro/eligibility/cyrebro-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Cyrebro's own page on 2026-11-09.
synthetic: false
tags:
- Security
- SOC
- Artificial Intelligence
- Managed Service
- SIEM
- Automation
---
