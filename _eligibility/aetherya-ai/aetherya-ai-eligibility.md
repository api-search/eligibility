---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not be subject to EU, UK, UN, or US sanctions or located in a sanctioned/embargoed territory.
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) and capable of forming a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Unlawful profiling or automated significant decisions
    text: Use outputs to unlawfully profile, score, or target individuals, or to take legal or similarly significant decisions about a person by automated means in breach of applicable law;
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
name: Aetherya
provenance_date: '2026-11-09'
provider_name: Aetherya
provider_slug: aetherya-ai
slug: aetherya-ai-eligibility
source_date: '2026-11-09'
source_filename: aetherya-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.aetherya.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aetherya\naid: aetherya-ai\nurl: https://www.aetherya.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not be subject to EU, UK, UN, or US sanctions or located in a sanctioned/embargoed territory.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) and capable of forming a\n    binding contract.\nrestricted_uses:\n- summary: Unlawful profiling or automated significant decisions\n  text: Use outputs to unlawfully profile, score, or target individuals, or to take legal or similarly significant\n\
  \    decisions about a person by automated means in breach of applicable law;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/aetherya-ai/eligibility/aetherya-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Aetherya's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Simulation
- Research
- Enterprise
- Platform
---
