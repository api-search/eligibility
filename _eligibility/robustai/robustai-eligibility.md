---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and capable of forming a legally binding agreement to use our Service.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a legally binding agreement to use our Service.
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
name: Robust.AI
provenance_date: '2026-11-10'
provider_name: Robust.AI
provider_slug: robustai
slug: robustai-eligibility
source_date: '2026-11-10'
source_filename: robustai-eligibility.yml
source_heading: Eligibility
source_page: https://www.robust.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Robust.AI\naid: robustai\nurl: https://www.robust.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a legally binding agreement to use our Service.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You\
  \ must be at least 18 years old and capable of forming a legally binding agreement to use our Service.\n"
source_yaml_url: https://artifacts.apis.io/robustai/eligibility/robustai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Robust.AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- Robotics
- Warehouse
- Manufacturing
- Logistics
- Fulfillment
- Artificial Intelligence
---
