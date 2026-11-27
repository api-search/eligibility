---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms apply to all users, including healthcare organizations, administrators, and authorized personnel.
    type: business
  minimum_age:
    text: you must be at least 18 years old and authorized by a subscribing healthcare organization
    value: '18'
  restricted_uses:
  - summary: Violating law including HIPAA
    text: Use the Services in violation of any applicable law or regulation, including HIPAA
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use our Services, you must be at least 18 years old and authorized by a subscribing healthcare organization.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beacon Health
provenance_date: '2026-11-09'
provider_name: Beacon Health
provider_slug: beacon-health
slug: beacon-health-eligibility
source_date: '2026-11-09'
source_filename: beacon-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.beaconhealth.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beacon Health\naid: beacon-health\nurl: https://www.beaconhealth.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Terms apply to all users, including healthcare organizations, administrators, and authorized personnel.\nrestricted_uses:\n- summary: Violating law including HIPAA\n  text: Use the Services in violation of any applicable law or regulation, including HIPAA\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use our Services, you must be at least 18 years old and authorized by a subscribing\
  \ healthcare organization.\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old and authorized by a subscribing healthcare organization\n"
source_yaml_url: https://artifacts.apis.io/beacon-health/eligibility/beacon-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Beacon Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Primary Care
- Value-Based Care
- Electronic Health Records
- Artificial Intelligence
- AI Agents
- Workflow Automation
- Risk Adjustment
- Prior Authorization
- HIPAA
- Y Combinator
---
