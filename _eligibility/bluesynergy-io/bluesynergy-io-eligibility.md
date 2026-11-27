---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If entering on behalf of an enterprise or entity, you represent and warrant that you possess full corporate authority to bind that entity.
    type: business
  - text: the legal entity or registered individual accessing our cognitive services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or malicious payloads
    text: Ingest unlawful, defamatory, infringing, or malicious software payloads into the thread buffer.
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
name: Blue Synergy
provenance_date: '2026-11-09'
provider_name: Blue Synergy
provider_slug: bluesynergy-io
slug: bluesynergy-io-eligibility
source_date: '2026-11-09'
source_filename: bluesynergy-io-eligibility.yml
source_heading: Eligibility
source_page: https://bluesynergy.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blue Synergy\naid: bluesynergy-io\nurl: https://bluesynergy.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If entering on behalf of an enterprise or entity, you represent and warrant that you possess full corporate\n    authority to bind that entity.\n- type: individual\n  text: the legal entity or registered individual accessing our cognitive services\nrestricted_uses:\n- summary: No unlawful or malicious payloads\n  text: Ingest unlawful, defamatory, infringing, or malicious software payloads into the thread buffer.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bluesynergy-io/eligibility/bluesynergy-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Blue Synergy's own page on 2026-11-09.
synthetic: false
tags:
- Enterprise AI
- AI Integration
- Workflow Orchestration
- Private RAG
- MedTech AI
- SaaS Platform
---
