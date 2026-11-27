---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms apply to all users, including builders, homeowners, and other individuals accessing our services, tools, content, or features.
    type: individual
  minimum_age:
    text: Our services are intended for individuals aged 18 years or older.
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
name: Omnee
provenance_date: '2026-11-10'
provider_name: Omnee
provider_slug: omnee
slug: omnee-eligibility
source_date: '2026-11-10'
source_filename: omnee-eligibility.yml
source_heading: Eligibility
source_page: https://www.omnee.ai/terms-privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Omnee\naid: omnee\nurl: https://www.omnee.ai/terms-privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Terms apply to all users, including builders, homeowners, and other individuals accessing our services,\n    tools, content, or features.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our services are intended for individuals aged 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/omnee/eligibility/omnee-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Omnee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Customer Service
- Homebuilding
- Real Estate
- Warranty
- Software-as-a-Service
- Conversational AI
---
