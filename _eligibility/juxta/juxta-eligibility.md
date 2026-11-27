---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users must be 18 years or older to access our services.
    type: individual
  - text: you have the legal authority to enter into these Terms on behalf of yourself or the organization you represent.
    type: business
  minimum_age:
    text: Users must be 18 years or older to access our services.
    value: 18 years
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
name: Juxta
provenance_date: '2026-11-09'
provider_name: Juxta
provider_slug: juxta
slug: juxta-eligibility
source_date: '2026-11-09'
source_filename: juxta-eligibility.yml
source_heading: Eligibility
source_page: https://www.juxta.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Juxta\naid: juxta\nurl: https://www.juxta.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users must be 18 years or older to access our services.\n- type: business\n  text: you have the legal authority to enter into these Terms on behalf of yourself or the organization you represent.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 18 years\n  text: Users must be 18 years or older to access our services.\n"
source_yaml_url: https://artifacts.apis.io/juxta/eligibility/juxta-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Juxta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Positioning
- Location
- Geospatial
- Indoor Positioning
- Asset Tracking
- Navigation
- Robotics
- Defense
- Logistics
- Healthcare
---
