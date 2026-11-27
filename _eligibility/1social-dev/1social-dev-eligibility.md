---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 to use 1Social.
    type: individual
  minimum_age:
    text: You must be at least 18 to use 1Social.
    value: '18'
  restricted_uses:
  - summary: Acceptable-use restrictions
    text: 'You must not use 1Social for: — spam, mass-following, artificial amplification, or fake engagement;'
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
name: 1Social
provenance_date: '2026-11-09'
provider_name: 1Social
provider_slug: 1social-dev
slug: 1social-dev-eligibility
source_date: '2026-11-09'
source_filename: 1social-dev-eligibility.yml
source_heading: Eligibility
source_page: https://1social.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1Social\naid: 1social-dev\nurl: https://1social.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 to use 1Social.\nrestricted_uses:\n- summary: Acceptable-use restrictions\n  text: 'You must not use 1Social for: — spam, mass-following, artificial amplification, or fake engagement;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 to use 1Social.\n"
source_yaml_url: https://artifacts.apis.io/1social-dev/eligibility/1social-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 1Social's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- AI Integration
- Automation
- Content Publishing
- ChatGPT
---
