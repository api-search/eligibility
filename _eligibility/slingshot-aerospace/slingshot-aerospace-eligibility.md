---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: are of legal age to form a binding contract
    type: individual
  minimum_age:
    text: THE SERVICES ARE NOT INTENDED FOR USERS UNDER THE AGE OF 13
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
name: Slingshot Aerospace
provenance_date: '2026-11-10'
provider_name: Slingshot Aerospace
provider_slug: slingshot-aerospace
slug: slingshot-aerospace-eligibility
source_date: '2026-11-10'
source_filename: slingshot-aerospace-eligibility.yml
source_heading: Eligibility
source_page: https://www.slingshot.space/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Slingshot Aerospace\naid: slingshot-aerospace\nurl: https://www.slingshot.space/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: are of legal age to form a binding contract\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: THE SERVICES ARE NOT INTENDED FOR USERS UNDER THE AGE OF 13\n"
source_yaml_url: https://artifacts.apis.io/slingshot-aerospace/eligibility/slingshot-aerospace-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Slingshot Aerospace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Space
- Aerospace
- Space Situational Awareness
- Satellite Tracking
- Orbital Intelligence
- Space Domain Awareness
- Defense
- Artificial Intelligence
- Data
---
