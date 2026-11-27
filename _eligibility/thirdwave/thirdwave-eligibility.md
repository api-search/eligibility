---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 (eighteen) years of age before you can use this website.
    type: individual
  minimum_age:
    text: You must be at least 18 (eighteen) years of age before you can use this website.
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
name: Thirdwave
provenance_date: '2026-11-10'
provider_name: Thirdwave
provider_slug: thirdwave
slug: thirdwave-eligibility
source_date: '2026-11-10'
source_filename: thirdwave-eligibility.yml
source_heading: Eligibility
source_page: https://thirdwave.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thirdwave\naid: thirdwave\nurl: https://thirdwave.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 (eighteen) years of age before you can use this website.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 (eighteen) years of age before you can use this website.\n"
source_yaml_url: https://artifacts.apis.io/thirdwave/eligibility/thirdwave-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Thirdwave's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Robotics
- Automation
- Warehouse
- Supply Chain
- Autonomous Vehicles
- Material Handling
---
