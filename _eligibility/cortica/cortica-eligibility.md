---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the person who access and uses our Website
    type: individual
  minimum_age:
    text: you represent and warrant that you are 18 years of age or older (or above the age of majority as determined by the applicable law in your jurisdiction of residency)
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: you may only use the Website for lawful purposes
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
name: Cortica
provenance_date: '2026-11-09'
provider_name: Cortica
provider_slug: cortica
slug: cortica-eligibility
source_date: '2026-11-09'
source_filename: cortica-eligibility.yml
source_heading: Eligibility
source_page: https://cortica.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cortica\naid: cortica\nurl: https://cortica.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the person who access and uses our Website\nrestricted_uses:\n- summary: Lawful purposes only\n  text: you may only use the Website for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years of age or older (or above the age of majority as determined\n    by the applicable law in your jurisdiction\
  \ of residency)\n"
source_yaml_url: https://artifacts.apis.io/cortica/eligibility/cortica-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cortica's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Computer Vision
- Machine Learning
- Autonomous Systems
- Venture Builder
- Israel
- Deep Tech
---
