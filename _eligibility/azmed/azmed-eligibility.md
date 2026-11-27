---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Access to Rayvolve is reserved for Healthcare Professionals who are legally allowed to use a Class IIA medical device in Europe or Class II in the USA.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Access limited to healthcare professionals
    text: Access to people not pertaining to this category is expressly prohibited.
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
name: AZmed
provenance_date: '2026-11-09'
provider_name: AZmed
provider_slug: azmed
slug: azmed-eligibility
source_date: '2026-11-09'
source_filename: azmed-eligibility.yml
source_heading: Eligibility
source_page: https://www.azmed.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AZmed\naid: azmed\nurl: https://www.azmed.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Access to Rayvolve is reserved for Healthcare Professionals who are legally allowed to use a Class IIA medical\n    device in Europe or Class II in the USA.\nrestricted_uses:\n- summary: Access limited to healthcare professionals\n  text: Access to people not pertaining to this category is expressly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/azmed/eligibility/azmed-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AZmed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Medical Imaging
- Artificial Intelligence
- Radiology
- Healthcare
- Diagnostics
- Machine Learning
---
