---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    - CH
    text: United States Dealside Inc; European Economic Area, United Kingdom, Switzerland Dealside BV (Belgium)
  entity_types:
  - text: the entity that executes an Order Form for the Services, expressly referencing this MSA
    type: business
  - text: the individual that signs up for and accesses the Subscription Service on a free trial basis
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for legal, financial, medical or safety-critical advice
    text: The Subscription Service is not intended to provide legal, financial, medical, or safety-critical advice and must not be relied upon as such.
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
name: Donna
provenance_date: '2026-11-09'
provider_name: Donna
provider_slug: donna
slug: donna-eligibility
source_date: '2026-11-09'
source_filename: donna-eligibility.yml
source_heading: Eligibility
source_page: https://www.askdonna.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Donna\naid: donna\nurl: https://www.askdonna.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  - CH\n  excluded: []\n  text: United States Dealside Inc; European Economic Area, United Kingdom, Switzerland Dealside BV (Belgium)\nentity_types:\n- type: business\n  text: the entity that executes an Order Form for the Services, expressly referencing this MSA\n- type: individual\n  text: the individual that signs up for and accesses the Subscription Service on a free trial basis\nrestricted_uses:\n- summary: Not for legal, financial, medical or safety-critical advice\n  text: The\
  \ Subscription Service is not intended to provide legal, financial, medical, or safety-critical advice\n    and must not be relied upon as such.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/donna/eligibility/donna-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Donna's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales
- Field Sales
- CRM
- Sales Enablement
- Voice AI
- Productivity
- Software-as-a-Service
- AI Assistant
---
