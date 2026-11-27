---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are physically located in the United States and within a jurisdiction in which we offer our Service
  entity_types:
  - text: you are at least eighteen (18) years of age
    type: individual
  - text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant that you are an authorized representative of the entity
    type: business
  minimum_age:
    text: you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: OUR SERVICE IS NOT INTENDED FOR EMERGENCY SITUATIONS. IN THE EVENT OF A MEDICAL EMERGENCY, PLEASE CALL 911 OR APPROPRIATE EMERGENCY RESPONDERS.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may ask a series of initial questions during registration. Based on your responses to these questions, we may determine that you are not eligible to utilize the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Virta Health
provenance_date: '2026-11-10'
provider_name: Virta Health
provider_slug: virta-health
slug: virta-health-eligibility
source_date: '2026-11-10'
source_filename: virta-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.virtahealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Virta Health\naid: virta-health\nurl: https://www.virtahealth.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are physically located in the United States and within a jurisdiction in which we offer our Service\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years of age\n- type: business\n  text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant\n    that you are an authorized representative of the entity\nrestricted_uses:\n- summary: Not for emergencies\n  text:\
  \ OUR SERVICE IS NOT INTENDED FOR EMERGENCY SITUATIONS. IN THE EVENT OF A MEDICAL EMERGENCY, PLEASE CALL 911\n    OR APPROPRIATE EMERGENCY RESPONDERS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may ask a series of initial questions during registration. Based on your responses to these questions,\n    we may determine that you are not eligible to utilize the Service.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/virta-health/eligibility/virta-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Virta Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Telehealth
- Diabetes
- Chronic Care
- Weight Loss
---
