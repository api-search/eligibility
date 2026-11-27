---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: CareerCorner is available in the United States (including US territories). Accounts registered from elsewhere aren't supported yet
  entity_types:
  - text: One account per person.
    type: individual
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
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
name: CareerCorner
provenance_date: '2026-11-09'
provider_name: CareerCorner
provider_slug: careercorner-ai
slug: careercorner-ai-eligibility
source_date: '2026-11-09'
source_filename: careercorner-ai-eligibility.yml
source_heading: Eligibility
source_page: https://careercorner.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CareerCorner\naid: careercorner-ai\nurl: https://careercorner.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: CareerCorner is available in the United States (including US territories). Accounts registered from elsewhere\n    aren't supported yet\nentity_types:\n- type: individual\n  text: One account per person.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/careercorner-ai/eligibility/careercorner-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from CareerCorner's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Job Search
- Coaching
- Careers
- Platform
- Company
---
