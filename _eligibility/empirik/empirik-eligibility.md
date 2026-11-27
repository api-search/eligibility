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
  - summary: US export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations
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
name: Empirik
provenance_date: '2026-11-09'
provider_name: Empirik
provider_slug: empirik
slug: empirik-eligibility
source_date: '2026-11-09'
source_filename: empirik-eligibility.yml
source_heading: Eligibility
source_page: https://empirik.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Empirik\naid: empirik\nurl: https://empirik.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: US export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services,\n    Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or\n    regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/empirik/eligibility/empirik-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Empirik's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Observability
- Change Management
- Platform Engineering
---
