---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: reside in the United States of America or any of its territories
  entity_types:
  - text: 'The Omada Programs and the Apps are available only to individuals who:'
    type: individual
  minimum_age:
    text: at least 13 years old for Omada for Joint & Muscle Health and at least 18 years old for the other Omada Programs
    value: '13'
  restricted_uses:
  - summary: Non-emergency use only
    text: THE SERVICES ARE FOR NON-EMERGENCY PURPOSES ONLY.
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
name: Omada Health
provenance_date: '2026-11-10'
provider_name: Omada Health
provider_slug: omada-health
slug: omada-health-eligibility
source_date: '2026-11-10'
source_filename: omada-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.omadahealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Omada Health\naid: omada-health\nurl: https://www.omadahealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: reside in the United States of America or any of its territories\nentity_types:\n- type: individual\n  text: 'The Omada Programs and the Apps are available only to individuals who:'\nrestricted_uses:\n- summary: Non-emergency use only\n  text: THE SERVICES ARE FOR NON-EMERGENCY PURPOSES ONLY.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: at least 13 years old\
  \ for Omada for Joint & Muscle Health and at least 18 years old for the other Omada\n    Programs\n"
source_yaml_url: https://artifacts.apis.io/omada-health/eligibility/omada-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Omada Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Health
- Virtual Care
- Chronic Disease Management
- Diabetes
- Hypertension
- Healthcare
- HIPAA
- Telehealth
---
