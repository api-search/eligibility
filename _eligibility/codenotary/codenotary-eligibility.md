---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you (either an individual or a legal entity)
    type: individual
  - text: you (either an individual or a legal entity)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You agree to fully comply with all applicable laws and regulations regarding export restrictions
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
name: Codenotary
provenance_date: '2026-11-09'
provider_name: Codenotary
provider_slug: codenotary
slug: codenotary-eligibility
source_date: '2026-11-09'
source_filename: codenotary-eligibility.yml
source_heading: Eligibility
source_page: https://codenotary.com/terms-of-service?hsLang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codenotary\naid: codenotary\nurl: https://codenotary.com/terms-of-service?hsLang=en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you (either an individual or a legal entity)\n- type: business\n  text: you (either an individual or a legal entity)\nrestricted_uses:\n- summary: Export restrictions\n  text: You agree to fully comply with all applicable laws and regulations regarding export restrictions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/codenotary/eligibility/codenotary-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Codenotary's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Cybersecurity
- Monitoring
- Enterprise
- Platform
---
