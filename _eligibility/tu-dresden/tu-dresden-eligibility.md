---
claim_count: 3
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
  - summary: Protected or confidential data
    text: Processing protected data or confidential information, unless the legal framework conditions are met
  - summary: Personal data by external parties
    text: The use of the artificial intelligence services involving personal data by external institutions or organizations is generally not permitted.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to the API requires an API key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TU Dresden
provenance_date: '2026-11-10'
provider_name: TU Dresden
provider_slug: tu-dresden
slug: tu-dresden-eligibility
source_date: '2026-11-10'
source_filename: tu-dresden-eligibility.yml
source_heading: Eligibility
source_page: https://llm.scads.ai/docs/legal/usage-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TU Dresden\naid: tu-dresden\nurl: https://llm.scads.ai/docs/legal/usage-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Protected or confidential data\n  text: Processing protected data or confidential information, unless the legal framework conditions are met\n- summary: Personal data by external parties\n  text: The use of the artificial intelligence services involving personal data by external institutions or organizations\n    is generally not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Access to the API requires an API key.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tu-dresden/eligibility/tu-dresden-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from TU Dresden's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- Germany
- Saxony
- TU9
- Research
- Research Data
- Research Computing
- Artificial Intelligence
- Identity Federation
- OAI-PMH
- Institutional Repository
- Open Access
---
