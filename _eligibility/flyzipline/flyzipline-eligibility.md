---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may not be used in or for the benefit of... any U.S. embargoed country or territory
  entity_types:
  - text: You must be at least eighteen (18) years old to use the Services, and capable of entering into a legally binding agreement on your behalf.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Services
    value: '18'
  restricted_uses:
  - summary: No resale or commercial use
    text: You will not sell, resell, rent or otherwise commercially use the Services provided by Zipline;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You are required to register for an account to use the Services. You must provide accurate and complete information to register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flyzipline
provenance_date: '2026-11-09'
provider_name: Flyzipline
provider_slug: flyzipline
slug: flyzipline-eligibility
source_date: '2026-11-09'
source_filename: flyzipline-eligibility.yml
source_heading: Eligibility
source_page: https://www.zipline.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flyzipline\naid: flyzipline\nurl: https://www.zipline.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services may not be used in or for the benefit of... any U.S. embargoed country or territory\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to use the Services, and capable of entering into a legally\n    binding agreement on your behalf.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority\
  \ to bind you to these Terms\nrestricted_uses:\n- summary: No resale or commercial use\n  text: You will not sell, resell, rent or otherwise commercially use the Services provided by Zipline;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You are required to register for an account to use the Services. You must provide accurate and complete\n    information to register for an account.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Services\n"
source_yaml_url: https://artifacts.apis.io/flyzipline/eligibility/flyzipline-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Flyzipline's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Drone Delivery
- Logistics
- Autonomous Systems
- Healthcare
- Robotics
- Last Mile Delivery
- Instant Logistics
---
