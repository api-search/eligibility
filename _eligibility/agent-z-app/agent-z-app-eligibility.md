---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: EDGE is not offered where its use would be unlawful.
  minimum_age:
    text: You must be of legal age in your jurisdiction and responsible for confirming that using EDGE is permitted where you live.
    value: legal age
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
name: EDGE
provenance_date: '2026-11-09'
provider_name: EDGE
provider_slug: agent-z-app
slug: agent-z-app-eligibility
source_date: '2026-11-09'
source_filename: agent-z-app-eligibility.yml
source_heading: Eligibility
source_page: https://edgetrading.live/disclaimer
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EDGE\naid: agent-z-app\nurl: https://edgetrading.live/disclaimer\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: EDGE is not offered where its use would be unlawful.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You must be of legal age in your jurisdiction and responsible for confirming that using EDGE is permitted\n    where you live.\n"
source_yaml_url: https://artifacts.apis.io/agent-z-app/eligibility/agent-z-app-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from EDGE's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Cryptocurrency
- Trading
- Automation
- Tokenization
---
