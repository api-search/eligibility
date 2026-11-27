---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users must be at least 16 years of age to use the Symptom Check and Illness Check modules.
    type: individual
  minimum_age:
    text: Users must be at least 16 years of age to use the Symptom Check and Illness Check modules.
    value: '16'
  restricted_uses:
  - summary: Under-16 and third-party use limits
    text: Use (i) by persons under the age of 16 and (ii) by persons over the age of 16 for third parties under the age of 10 is prohibited and constitutes misuse outside the intended purpose.
  - summary: Health Check adult-only; no third-party use
    text: To use the Health Check module, users must be at least 18 years of age. Use of this module for third parties is not permitted.
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
name: Xund
provenance_date: '2026-11-10'
provider_name: Xund
provider_slug: xund
slug: xund-eligibility
source_date: '2026-11-10'
source_filename: xund-eligibility.yml
source_heading: Eligibility
source_page: https://xund.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xund\naid: xund\nurl: https://xund.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users must be at least 16 years of age to use the Symptom Check and Illness Check modules.\nrestricted_uses:\n- summary: Under-16 and third-party use limits\n  text: Use (i) by persons under the age of 16 and (ii) by persons over the age of 16 for third parties under the\n    age of 10 is prohibited and constitutes misuse outside the intended purpose.\n- summary: Health Check adult-only; no third-party use\n  text:\
  \ To use the Health Check module, users must be at least 18 years of age. Use of this module for third parties\n    is not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Users must be at least 16 years of age to use the Symptom Check and Illness Check modules.\n"
source_yaml_url: https://artifacts.apis.io/xund/eligibility/xund-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Xund's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Artificial Intelligence
- Healthcare
- Diagnostics
- Risk Assessment
---
