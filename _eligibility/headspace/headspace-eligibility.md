---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are located outside of the United States, you may have access to our meditation, mindfulness, sleep and movement content and mental health coaching only.
  entity_types:
  - text: Our Products and Services are intended for individuals at least 18 years of age.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for emergencies
    text: YOU AGREE THAT THE PRODUCTS AND SERVICES ARE NOT INTENDED TO BE USED IN A MEDICAL EMERGENCY.
  - summary: Commercial use excluded
    text: The Products and Services are not intended for your commercial use.
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
name: Headspace
provenance_date: '2026-11-09'
provider_name: Headspace
provider_slug: headspace
slug: headspace-eligibility
source_date: '2026-11-09'
source_filename: headspace-eligibility.yml
source_heading: Eligibility
source_page: https://www.headspace.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Headspace\naid: headspace\nurl: https://www.headspace.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you are located outside of the United States, you may have access to our meditation, mindfulness, sleep\n    and movement content and mental health coaching only.\nentity_types:\n- type: individual\n  text: Our Products and Services are intended for individuals at least 18 years of age.\nrestricted_uses:\n- summary: Not for emergencies\n  text: YOU AGREE THAT THE PRODUCTS AND SERVICES ARE NOT INTENDED TO BE USED IN A MEDICAL EMERGENCY.\n\
  - summary: Commercial use excluded\n  text: The Products and Services are not intended for your commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/headspace/eligibility/headspace-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Headspace's own page on 2026-11-09.
synthetic: false
tags:
- Mental Health
- Meditation
- Sleep
- Mindfulness
- Therapy
- Coaching
- Psychiatry
- EAP
- Consumer
- B2B
- Wellness
---
