---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: на территории всего мира
  entity_types:
  - text: любому физическому лицу
    type: individual
  minimum_age:
    text: null
    value: null
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
name: AnyLLM
provenance_date: '2026-11-09'
provider_name: AnyLLM
provider_slug: anyllm
slug: anyllm-eligibility
source_date: '2026-11-09'
source_filename: anyllm-eligibility.yml
source_heading: Eligibility
source_page: https://anyllm.tech/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnyLLM\naid: anyllm\nurl: https://anyllm.tech/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: на территории всего мира\nentity_types:\n- type: individual\n  text: любому физическому лицу\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anyllm/eligibility/anyllm-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from AnyLLM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Open Source
- Browser
---
