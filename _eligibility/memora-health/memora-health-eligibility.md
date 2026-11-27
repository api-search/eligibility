---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We operate the Service from our offices in California, and we make no representation that Materials included in the Service are appropriate or available for use in other locations.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: OUR SERVICE IS NOT INTENDED FOR EMERGENCY SITUATIONS.
  - summary: Not for medical emergencies
    text: DO NOT USE THE SERVICE FOR MEDICAL EMERGENCIES.
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
name: Memora Health
provenance_date: '2026-11-10'
provider_name: Memora Health
provider_slug: memora-health
slug: memora-health-eligibility
source_date: '2026-11-10'
source_filename: memora-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.memorahealth.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Memora Health\naid: memora-health\nurl: https://www.memorahealth.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We operate the Service from our offices in California, and we make no representation that Materials included\n    in the Service are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they\
  \ have authority to bind you to these Terms\nrestricted_uses:\n- summary: Not for emergencies\n  text: OUR SERVICE IS NOT INTENDED FOR EMERGENCY SITUATIONS.\n- summary: Not for medical emergencies\n  text: DO NOT USE THE SERVICE FOR MEDICAL EMERGENCIES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/memora-health/eligibility/memora-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Memora Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Patient Engagement
- Care Management
- Remote Patient Monitoring
- Clinical Workflow Automation
- Artificial Intelligence
---
