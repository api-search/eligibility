---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only individuals ages 18 and older may use the System.
    type: individual
  minimum_age:
    text: Only individuals ages 18 and older may use the System.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: You shall not use or access the System if you are barred from doing so under applicable law or have previously been removed from the System, nor shall you use the System in any manner that violates local, state, or federal law, regulation, or court order.
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
name: JusticeText
provenance_date: '2026-11-09'
provider_name: JusticeText
provider_slug: justicetext
slug: justicetext-eligibility
source_date: '2026-11-09'
source_filename: justicetext-eligibility.yml
source_heading: Eligibility
source_page: https://www.justicetext.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JusticeText\naid: justicetext\nurl: https://www.justicetext.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only individuals ages 18 and older may use the System.\nrestricted_uses:\n- summary: Unlawful use\n  text: You shall not use or access the System if you are barred from doing so under applicable law or have previously\n    been removed from the System, nor shall you use the System in any manner that violates local, state, or federal\n    law, regulation, or court order.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Only individuals ages 18 and older may use the System.\n"
source_yaml_url: https://artifacts.apis.io/justicetext/eligibility/justicetext-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from JusticeText's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Criminal Justice
- Evidence Management
- Transcription
- Artificial Intelligence
- Public Defenders
---
