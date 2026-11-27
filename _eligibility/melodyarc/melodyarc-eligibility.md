---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you must be able to enter into a legally binding contract, and represent that you are at least 18 years old
    type: individual
  - text: if a business, duly organized and legally in good standing
    type: business
  minimum_age:
    text: represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: export, re-export, import, or transfer any part of the Services except as authorized by United States law, the export control laws of your jurisdiction, and any other applicable laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to refuse registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MelodyArc
provenance_date: '2026-11-10'
provider_name: MelodyArc
provider_slug: melodyarc
slug: melodyarc-eligibility
source_date: '2026-11-10'
source_filename: melodyarc-eligibility.yml
source_heading: Eligibility
source_page: https://melodyarc.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MelodyArc\naid: melodyarc\nurl: https://melodyarc.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you must be able to enter into a legally binding contract, and represent that you are at least 18 years\n    old\n- type: business\n  text: if a business, duly organized and legally in good standing\nrestricted_uses:\n- summary: Export restrictions\n  text: export, re-export, import, or transfer any part of the Services except as authorized by United States law,\n    the export control laws of your jurisdiction,\
  \ and any other applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to refuse registration.\nminimum_age:\n  value: '18'\n  text: represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/melodyarc/eligibility/melodyarc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from MelodyArc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Workflow Automation
- Orchestration
- AI Agents
- Governance
- Enterprise
- Human-in-the-Loop
---
