---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to hold or use a Learning Lab account.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to hold or use a Learning Lab account.
    value: '18'
  restricted_uses:
  - summary: Emergency use prohibited
    text: THE SITES ARE NOT DESIGNED OR INTENDED FOR MEDICAL EMERGENCIES.
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
name: Insito Health
provenance_date: '2026-11-09'
provider_name: Insito Health
provider_slug: insito-health
slug: insito-health-eligibility
source_date: '2026-11-09'
source_filename: insito-health-eligibility.yml
source_heading: Eligibility
source_page: https://insitehealth.net/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Insito Health\naid: insito-health\nurl: https://insitehealth.net/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to hold or use a Learning Lab account.\nrestricted_uses:\n- summary: Emergency use prohibited\n  text: THE SITES ARE NOT DESIGNED OR INTENDED FOR MEDICAL EMERGENCIES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to hold or use a Learning Lab account.\n"
source_yaml_url: https://artifacts.apis.io/insito-health/eligibility/insito-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Insito Health's own page on 2026-11-09.
synthetic: false
tags:
- Mental Health
- Education
- Platform
- Telehealth
- Software-as-a-Service
---
