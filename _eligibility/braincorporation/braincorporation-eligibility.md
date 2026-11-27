---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Brain offers the Services to businesses, such as Brain Licensees, not consumers.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable in your country of residence of entering into a legal binding agreement to use the Services.
    value: '18'
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
name: Braincorporation
provenance_date: '2026-11-09'
provider_name: Braincorporation
provider_slug: braincorporation
slug: braincorporation-eligibility
source_date: '2026-11-09'
source_filename: braincorporation-eligibility.yml
source_heading: Eligibility
source_page: https://www.braincorp.com/legal/brain-portal-website-app-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Braincorporation\naid: braincorporation\nurl: https://www.braincorp.com/legal/brain-portal-website-app-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Brain offers the Services to businesses, such as Brain Licensees, not consumers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable in your country of residence of entering into a legal binding\n    agreement to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/braincorporation/eligibility/braincorporation-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Braincorporation's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Robotics
- Autonomous
- Enterprise
- Platform
---
