---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: The Service and our Apps are not directed to children. If you are under 13 years of age (or under 16 years of age if you live in the European Union), you are not authorized to use the Service
    type: individual
  minimum_age:
    text: If you are under 13 years of age (or under 16 years of age if you live in the European Union), you are not authorized to use the Service, including any Apps, with or without registering.
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
name: Illumix
provenance_date: '2026-11-09'
provider_name: Illumix
provider_slug: illumix
slug: illumix-eligibility
source_date: '2026-11-09'
source_filename: illumix-eligibility.yml
source_heading: Eligibility
source_page: https://www.illumix.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Illumix\naid: illumix\nurl: https://www.illumix.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo\nentity_types:\n- type: individual\n  text: The Service and our Apps are not directed to children. If you are under 13 years of age (or under 16 years\n    of age if you live in the European Union), you are not authorized to use the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: If you are under 13 years of age (or under 16 years of age if you live in the European Union), you are not\n    authorized to use the Service, including any Apps, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/illumix/eligibility/illumix-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Illumix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Spatial AI
- Augmented Reality
- Computer Vision
- Localization
- Edge AI
- Robotics
- Wearables
- Extended Reality
---
