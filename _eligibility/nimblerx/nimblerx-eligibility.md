---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To use the Services, you must be at least 18 years old and reside in the United States.
  entity_types:
  - text: The Services are designed primarily for individual patients
    type: individual
  minimum_age:
    text: you must be at least 18 years old and reside in the United States
    value: '18'
  restricted_uses:
  - summary: Business Users evaluation only
    text: Your use is for informational or evaluation purposes only and not for delivering patient care
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
name: Nimblerx
provenance_date: '2026-11-10'
provider_name: Nimblerx
provider_slug: nimblerx
slug: nimblerx-eligibility
source_date: '2026-11-10'
source_filename: nimblerx-eligibility.yml
source_heading: Eligibility
source_page: https://www.nimblerx.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nimblerx\naid: nimblerx\nurl: https://www.nimblerx.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To use the Services, you must be at least 18 years old and reside in the United States.\nentity_types:\n- type: individual\n  text: The Services are designed primarily for individual patients\nrestricted_uses:\n- summary: Business Users evaluation only\n  text: Your use is for informational or evaluation purposes only and not for delivering patient care\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: you must be at least 18 years old and reside in the United States\n"
source_yaml_url: https://artifacts.apis.io/nimblerx/eligibility/nimblerx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Nimblerx's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pharmacy
- Healthcare
- Prescriptions
- Digital Health
- Medication Adherence
- Pharmacy Software
- Ecommerce Checkout
---
