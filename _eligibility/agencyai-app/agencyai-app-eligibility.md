---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself or your business.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
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
name: Agency AI
provenance_date: '2026-11-09'
provider_name: Agency AI
provider_slug: agencyai-app
slug: agencyai-app-eligibility
source_date: '2026-11-09'
source_filename: agencyai-app-eligibility.yml
source_heading: Eligibility
source_page: https://agencyai.app/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agency AI\naid: agencyai-app\nurl: https://agencyai.app/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself\n    or your business.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/agencyai-app/eligibility/agencyai-app-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Agency AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Advertising
- Shopify
- Automation
- Marketing
---
