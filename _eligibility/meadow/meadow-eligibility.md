---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least [13] years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least [13] years old to use the Service.
    value: '13'
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
name: Meadow
provenance_date: '2026-11-10'
provider_name: Meadow
provider_slug: meadow
slug: meadow-eligibility
source_date: '2026-11-10'
source_filename: meadow-eligibility.yml
source_heading: Eligibility
source_page: https://www.meadowfi.com/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meadow\naid: meadow\nurl: https://www.meadowfi.com/legal/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least [13] years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority\
  \ to bind you to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least [13] years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/meadow/eligibility/meadow-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Meadow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Education
- Higher Education
- Student Payments
- Billing
- EdTech
- Payments
---
