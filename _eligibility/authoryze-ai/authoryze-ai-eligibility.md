---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter a binding contract to use Authoryze.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to enter a binding contract to use Authoryze.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: Authoryze may not be used by or on behalf of any individual or entity subject to U.S., U.K., or EU sanctions.
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
name: Authoryze
provenance_date: '2026-11-09'
provider_name: Authoryze
provider_slug: authoryze-ai
slug: authoryze-ai-eligibility
source_date: '2026-11-09'
source_filename: authoryze-ai-eligibility.yml
source_heading: Eligibility
source_page: https://authoryze.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Authoryze\naid: authoryze-ai\nurl: https://authoryze.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter a binding contract to use Authoryze.\nrestricted_uses:\n- summary: Sanctioned persons\n  text: Authoryze may not be used by or on behalf of any individual or entity subject to U.S., U.K., or EU sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter\
  \ a binding contract to use Authoryze.\n"
source_yaml_url: https://artifacts.apis.io/authoryze-ai/eligibility/authoryze-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Authoryze's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Payments
- Artificial Intelligence
- Security
- Platform
---
