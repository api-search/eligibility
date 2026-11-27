---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer must be at least 18 years of age or the age of majority in Customer’s jurisdiction.
    type: individual
  - text: the individual, organization and/or or entity specified on the applicable order form
    type: business
  minimum_age:
    text: Customer must be at least 18 years of age or the age of majority in Customer’s jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Use by under-13s and minors
    text: the Beautiful.ai Services are not intended for use by individuals under the age of 13, or the equivalent minimum age in the relevant jurisdiction.
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
name: beautiful.ai
provenance_date: '2026-11-09'
provider_name: beautiful.ai
provider_slug: beautifulai
slug: beautifulai-eligibility
source_date: '2026-11-09'
source_filename: beautifulai-eligibility.yml
source_heading: Eligibility
source_page: https://www.beautiful.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: beautiful.ai\naid: beautifulai\nurl: https://www.beautiful.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Customer must be at least 18 years of age or the age of majority in Customer’s jurisdiction.\n- type: business\n  text: the individual, organization and/or or entity specified on the applicable order form\nrestricted_uses:\n- summary: Use by under-13s and minors\n  text: the Beautiful.ai Services are not intended for use by individuals under the age of 13, or the equivalent\n    minimum age in the relevant\
  \ jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Customer must be at least 18 years of age or the age of majority in Customer’s jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/beautifulai/eligibility/beautifulai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from beautiful.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Presentations
- Slides
- Design
- Productivity
- Collaboration
- Software-as-a-Service
---
