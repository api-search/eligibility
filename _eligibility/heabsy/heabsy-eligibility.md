---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Heabsy Platform is offered only to businesses, sole traders, and other professionals acting in the course of their trade or profession
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AI Act prohibited practices
    text: You must not use the Service, or enable any end user to use it, for practices prohibited under Article 5 of Regulation (EU) 2024/1689
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
name: Heabsy
provenance_date: '2026-11-09'
provider_name: Heabsy
provider_slug: heabsy
slug: heabsy-eligibility
source_date: '2026-11-09'
source_filename: heabsy-eligibility.yml
source_heading: Eligibility
source_page: https://heabsy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Heabsy\naid: heabsy\nurl: https://heabsy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Heabsy Platform is offered only to businesses, sole traders, and other professionals acting in the course\n    of their trade or profession\nrestricted_uses:\n- summary: AI Act prohibited practices\n  text: You must not use the Service, or enable any end user to use it, for practices prohibited under Article 5\n    of Regulation (EU) 2024/1689\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/heabsy/eligibility/heabsy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Heabsy's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Inference
- OpenAI-Compatible
- EU-regulated
- Software-as-a-Service
---
