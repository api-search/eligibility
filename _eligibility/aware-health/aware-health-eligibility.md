---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users must be at least 12 years old to use the Platform.
    type: individual
  minimum_age:
    text: Users must be at least 12 years old to use the Platform. For users between 12 and 18, parental or guardian consent is required.
    value: '12'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Aware Health is not responsible for verifying the age of users
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aware Health
provenance_date: '2026-11-09'
provider_name: Aware Health
provider_slug: aware-health
slug: aware-health-eligibility
source_date: '2026-11-09'
source_filename: aware-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.awarehealth.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aware Health\naid: aware-health\nurl: https://www.awarehealth.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users must be at least 12 years old to use the Platform.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Aware Health is not responsible for verifying the age of users\nminimum_age:\n  value: '12'\n  text: Users must be at least 12 years old to use the Platform. For users between 12 and 18, parental or guardian\n    consent is required.\n"
source_yaml_url: https://artifacts.apis.io/aware-health/eligibility/aware-health-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Aware Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Musculoskeletal
- MSK Care
- Virtual Care
- Telehealth
- Artificial Intelligence
- Employee Benefits
---
