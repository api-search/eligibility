---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use Saka for lawful business purposes and only if you can enter a binding agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer-reporting decisions
    text: use records for credit, employment, insurance, housing eligibility, or other decisions governed by consumer-reporting law
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
name: saka-run
provenance_date: '2026-11-10'
provider_name: saka-run
provider_slug: saka-run
slug: saka-run-eligibility
source_date: '2026-11-10'
source_filename: saka-run-eligibility.yml
source_heading: Eligibility
source_page: https://saka.run/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: saka-run\naid: saka-run\nurl: https://saka.run/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Use Saka for lawful business purposes and only if you can enter a binding agreement.\nrestricted_uses:\n- summary: Consumer-reporting decisions\n  text: use records for credit, employment, insurance, housing eligibility, or other decisions governed by consumer-reporting\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/saka-run/eligibility/saka-run-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from saka-run's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Prospecting
- Marketing
- Software-as-a-Service
---
