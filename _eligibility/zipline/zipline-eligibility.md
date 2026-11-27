---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years old to use the Services, and capable of entering into a legally binding agreement on your behalf.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Services
    value: '18'
  restricted_uses:
  - summary: No pharmacy or medical advice use
    text: ZIPLINE IS NOT A PHARMACY OR HEALTHCARE PROVIDER
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
name: Zipline
provenance_date: '2026-11-10'
provider_name: Zipline
provider_slug: zipline
slug: zipline-eligibility
source_date: '2026-11-10'
source_filename: zipline-eligibility.yml
source_heading: Eligibility
source_page: https://www.zipline.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zipline\naid: zipline\nurl: https://www.zipline.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to use the Services, and capable of entering into a legally\n    binding agreement on your behalf.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: No pharmacy or medical advice use\n  text:\
  \ ZIPLINE IS NOT A PHARMACY OR HEALTHCARE PROVIDER\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Services\n"
source_yaml_url: https://artifacts.apis.io/zipline/eligibility/zipline-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zipline's own page on 2026-11-10.
synthetic: false
tags:
- Drones
- Autonomous Aircraft
- Drone Delivery
- Unmanned Aerial Systems
- Autonomous Logistics
- Last Mile Delivery
- Quick Commerce
- Healthcare Logistics
- Medical Delivery
- Blood Delivery
- Vaccine Delivery
- Retail Delivery
- Restaurant Delivery
- Aviation
- BVLOS
- Detect And Avoid
- VTOL
- Robotics
- Hardware
---
