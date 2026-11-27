---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Power
    type: individual
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Not for diagnosis or treatment
    text: Any content on the Services is not marketed, promoted or otherwise intended to be used to diagnose any disease or other condition, or to cure, mitigate, treat, or prevent any disease.
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
name: Power
provenance_date: '2026-11-10'
provider_name: Power
provider_slug: power
slug: power-eligibility
source_date: '2026-11-10'
source_filename: power-eligibility.yml
source_heading: Eligibility
source_page: https://www.withpower.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Power\naid: power\nurl: https://www.withpower.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Power\nrestricted_uses:\n- summary: Not for diagnosis or treatment\n  text: Any content on the Services is not marketed, promoted or otherwise intended to be used to diagnose any disease\n    or other condition, or to cure, mitigate, treat, or prevent any disease.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/power/eligibility/power-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Power's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Clinical Trials
- Healthcare
- Clinical Research
- Patient Matching
- Health
---
