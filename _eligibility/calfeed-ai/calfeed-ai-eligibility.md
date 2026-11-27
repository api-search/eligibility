---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One person or legal entity per account.
    type: individual
  minimum_age:
    text: You must be 13 or older.
    value: '13'
  restricted_uses:
  - summary: Illegal or infringing content
    text: Use the Service for illegal activity or to publish illegal content.
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
name: Calfeed
provenance_date: '2026-11-09'
provider_name: Calfeed
provider_slug: calfeed-ai
slug: calfeed-ai-eligibility
source_date: '2026-11-09'
source_filename: calfeed-ai-eligibility.yml
source_heading: Eligibility
source_page: https://calfeed.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calfeed\naid: calfeed-ai\nurl: https://calfeed.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One person or legal entity per account.\nrestricted_uses:\n- summary: Illegal or infringing content\n  text: Use the Service for illegal activity or to publish illegal content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 or older.\n"
source_yaml_url: https://artifacts.apis.io/calfeed-ai/eligibility/calfeed-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Calfeed's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Productivity
- Scheduling
- Web App
---
