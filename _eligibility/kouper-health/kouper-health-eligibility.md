---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is for personal, non-commercial use within the United States.
  entity_types:
  - text: Registration. You agree to provide accurate, current, and complete information, and you must be at least 18 years old.
    type: individual
  minimum_age:
    text: you must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: The Service is for personal, non-commercial use within the United States.
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
name: Kouper Health
provenance_date: '2026-11-09'
provider_name: Kouper Health
provider_slug: kouper-health
slug: kouper-health-eligibility
source_date: '2026-11-09'
source_filename: kouper-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.kouperhealth.com/content/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kouper Health\naid: kouper-health\nurl: https://www.kouperhealth.com/content/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is for personal, non-commercial use within the United States.\nentity_types:\n- type: individual\n  text: Registration. You agree to provide accurate, current, and complete information, and you must be at least\n    18 years old.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: The Service is for personal, non-commercial use within the United States.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/kouper-health/eligibility/kouper-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kouper Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Tech
- Artificial Intelligence
- AI Agents
- Care Coordination
- Care Transitions
- Patient Engagement
- Electronic Health Records
- Patient Access
- Post-Acute Care
- Care Management
---
