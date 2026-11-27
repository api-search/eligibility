---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Sesame services are only intended for users in the United States.
  entity_types:
  - text: Our Service is currently only available to individuals who are located in states in which we offer the Service, are at least eighteen (18) years of age or older
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    value: '18'
  restricted_uses:
  - summary: Emergencies
    text: USE OF OUR SERVICES IS NOT APPROPRIATE FOR EMERGENCIES.
  - summary: Controlled substances
    text: Please note that Providers do not prescribe controlled substances as part of the Sesame prescription services.
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
name: Sesame
provenance_date: '2026-11-10'
provider_name: Sesame
provider_slug: sesame
slug: sesame-eligibility
source_date: '2026-11-10'
source_filename: sesame-eligibility.yml
source_heading: Eligibility
source_page: https://sesamecare.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sesame\naid: sesame\nurl: https://sesamecare.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Sesame services are only intended for users in the United States.\nentity_types:\n- type: individual\n  text: Our Service is currently only available to individuals who are located in states in which we offer the Service,\n    are at least eighteen (18) years of age or older\nrestricted_uses:\n- summary: Emergencies\n  text: USE OF OUR SERVICES IS NOT APPROPRIATE FOR EMERGENCIES.\n- summary: Controlled substances\n  text: Please note that Providers\
  \ do not prescribe controlled substances as part of the Sesame prescription services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/sesame/eligibility/sesame-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Sesame's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Telehealth
- Healthcare
- Digital Health
- Marketplace
- Consumer Health
- Prescriptions
---
