---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Coach off-platform contact
    text: if you are a Coach, directly contact any Client or third party that you are introduced to through the Service
  - summary: Competitive use of outputs
    text: use the Service or any outputs of AI Technologies (including AI-generated summaries, recommendations, search results, or other outputs) to develop, train, fine-tune, benchmark, evaluate, or improve any products or services that are competitive with or a substitute for any Leland product or service
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your application to register for an account will be approved or rejected by us in our sole discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Leland
provenance_date: '2026-11-09'
provider_name: Leland
provider_slug: leland
slug: leland-eligibility
source_date: '2026-11-09'
source_filename: leland-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinleland.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leland\naid: leland\nurl: https://www.joinleland.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Coach off-platform contact\n  text: if you are a Coach, directly contact any Client or third party that you are introduced to through the Service\n- summary: Competitive use of outputs\n  text: use the Service or any outputs of AI Technologies (including AI-generated summaries, recommendations, search\n    results, or other\
  \ outputs) to develop, train, fine-tune, benchmark, evaluate, or improve any products or services\n    that are competitive with or a substitute for any Leland product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your application to register for an account will be approved or rejected by us in our sole discretion\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/leland/eligibility/leland-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Leland's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Coaching
- Career Development
- Admissions
- Test Preparation
- Marketplace
- E-Learning
- Talent
- Artificial Intelligence
---
