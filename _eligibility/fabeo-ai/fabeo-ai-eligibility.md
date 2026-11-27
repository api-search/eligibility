---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account or use the Service.
    type: individual
  - text: use the Service for your internal business purposes or on behalf of your clients (if you are an agency)
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account or use the Service.
    value: '18'
  restricted_uses:
  - summary: Likeness and impersonation restrictions
    text: will not use the Service to impersonate any person, create non-consensual intimate or sexual content, or create content intended to deceive, defame, harass, or mislead viewers
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
name: Fabeo
provenance_date: '2026-11-09'
provider_name: Fabeo
provider_slug: fabeo-ai
slug: fabeo-ai-eligibility
source_date: '2026-11-09'
source_filename: fabeo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://fabeo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fabeo\naid: fabeo-ai\nurl: https://fabeo.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account or use the Service.\n- type: business\n  text: use the Service for your internal business purposes or on behalf of your clients (if you are an agency)\nrestricted_uses:\n- summary: Likeness and impersonation restrictions\n  text: will not use the Service to impersonate any person, create non-consensual intimate or sexual content, or\n    create content intended to deceive, defame,\
  \ harass, or mislead viewers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/fabeo-ai/eligibility/fabeo-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fabeo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video Generation
- Agency Tools
- Automation
- Creative
---
