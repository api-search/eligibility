---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are starting your company from Europe.
  entity_types:
  - text: You are starting your company from Europe.
    type: business
  minimum_age:
    text: You are 25 years old or younger.
    value: null
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
name: Project Europe
provenance_date: '2026-11-10'
provider_name: Project Europe
provider_slug: project-europe
slug: project-europe-eligibility
source_date: '2026-11-10'
source_filename: project-europe-eligibility.yml
source_heading: Eligibility
source_page: https://www.projecteurope.co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Project Europe\naid: project-europe\nurl: https://www.projecteurope.co/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are starting your company from Europe.\nentity_types:\n- type: business\n  text: You are starting your company from Europe.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You are 25 years old or younger.\n"
source_yaml_url: https://artifacts.apis.io/project-europe/eligibility/project-europe-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Project Europe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Venture Capital
- Startups
- Founders
- Europe
- Community
---
