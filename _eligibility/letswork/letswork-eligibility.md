---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The availability of all or part of our Platform may be limited based on geographic, age, or other criteria as we may establish from time to time. You further understand that the Platform may not be available in every geography.
  entity_types:
  - text: To register on our Platform or mobile application you must be 18 years or older. Only one registration is allowed per person
    type: individual
  - text: If you have express permission from Letswork to open or use an account on behalf of a company, entity, or organization (a “Subscribing Organization”), then you represent and warrant that you are an authorized representative of such organization
    type: business
  minimum_age:
    text: For example, you must be 21 years of age or older to use the Platform and/or purchase a Letswork subscription.
    value: '21'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: You must not use or exploit the Platform for commercial purposes.
  - summary: UAE residency
    text: (c) that you will remain a resident of the UAE for the duration of your use of the Platform.
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
name: Letswork
provenance_date: '2026-11-09'
provider_name: Letswork
provider_slug: letswork
slug: letswork-eligibility
source_date: '2026-11-09'
source_filename: letswork-eligibility.yml
source_heading: Eligibility
source_page: https://www.letswork.io/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Letswork\naid: letswork\nurl: https://www.letswork.io/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The availability of all or part of our Platform may be limited based on geographic, age, or other criteria\n    as we may establish from time to time. You further understand that the Platform may not be available in every\n    geography.\nentity_types:\n- type: individual\n  text: To register on our Platform or mobile application you must be 18 years or older. Only one registration is\n    allowed per person\n- type: business\n  text: If you have express permission\
  \ from Letswork to open or use an account on behalf of a company, entity, or\n    organization (a “Subscribing Organization”), then you represent and warrant that you are an authorized representative\n    of such organization\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: You must not use or exploit the Platform for commercial purposes.\n- summary: UAE residency\n  text: (c) that you will remain a resident of the UAE for the duration of your use of the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: For example, you must be 21 years of age or older to use the Platform and/or purchase a Letswork subscription.\n"
source_yaml_url: https://artifacts.apis.io/letswork/eligibility/letswork-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Letswork's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Co-Working
- Workspace
- Booking
- Marketplace
- Real Estate
- Productivity
- Future Of Work
- Travel
---
