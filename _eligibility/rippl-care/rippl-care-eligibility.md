---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you can form a legally binding contract with us
    type: individual
  minimum_age:
    text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions)
    value: '18'
  restricted_uses:
  - summary: No minors without parental supervision
    text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions) in any applicable jurisdiction (a “ Minor ”) is strictly prohibited
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
name: Rippl Care *
provenance_date: '2026-11-10'
provider_name: Rippl Care *
provider_slug: rippl-care
slug: rippl-care-eligibility
source_date: '2026-11-10'
source_filename: rippl-care-eligibility.yml
source_heading: Eligibility
source_page: https://www.ripplcare.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rippl Care *\naid: rippl-care\nurl: https://www.ripplcare.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you can form a legally binding contract with us\nrestricted_uses:\n- summary: No minors without parental supervision\n  text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions)\n    in any applicable jurisdiction (a “ Minor ”) is strictly prohibited\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions)\n"
source_yaml_url: https://artifacts.apis.io/rippl-care/eligibility/rippl-care-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rippl Care *'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Healthcare
- Behavioral Health
- Dementia Care
- Senior Care
- Value-Based Care
- Telehealth
---
