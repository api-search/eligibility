---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use, probing, reselling
    text: You agree not to use Okapi to break any law, to probe or disrupt our systems, or to resell access without our written permission.
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
name: Okapi
provenance_date: '2026-11-10'
provider_name: Okapi
provider_slug: okapi-bot
slug: okapi-bot-eligibility
source_date: '2026-11-10'
source_filename: okapi-bot-eligibility.yml
source_heading: Eligibility
source_page: https://www.okapi.bot/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Okapi\naid: okapi-bot\nurl: https://www.okapi.bot/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use, probing, reselling\n  text: You agree not to use Okapi to break any law, to probe or disrupt our systems, or to resell access without\n    our written permission.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/okapi-bot/eligibility/okapi-bot-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Okapi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- API Change Management
- Breaking Changes
- Deprecation
- GitHub App
- Developer Tools
- API Monitoring
- AI Agents
---
