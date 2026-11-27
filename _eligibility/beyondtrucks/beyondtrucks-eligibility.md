---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  - text: BY ACCESSING OR USING THE SITE, YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT)
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: No abusive or illegal use
    text: you use the Services in a way that we determine, on our sole discretion, is abusive or disrupts or threatens the performance or availability of the Service
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
name: BeyondTrucks
provenance_date: '2026-11-09'
provider_name: BeyondTrucks
provider_slug: beyondtrucks
slug: beyondtrucks-eligibility
source_date: '2026-11-09'
source_filename: beyondtrucks-eligibility.yml
source_heading: Eligibility
source_page: https://www.beyondtrucks.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeyondTrucks\naid: beyondtrucks\nurl: https://www.beyondtrucks.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.\n- type: business\n  text: BY ACCESSING OR USING THE SITE, YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY\
  \ THAT\n    YOU REPRESENT)\nrestricted_uses:\n- summary: No abusive or illegal use\n  text: you use the Services in a way that we determine, on our sole discretion, is abusive or disrupts or threatens\n    the performance or availability of the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/beyondtrucks/eligibility/beyondtrucks-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from BeyondTrucks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- Artificial Intelligence
- Logistics
- Fleet Management
---
