---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older, or the age of majority where you live.
    type: individual
  minimum_age:
    text: You must be 18 or older, or the age of majority where you live.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You agree to use the Platform lawfully and responsibly.
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
name: vivioo-io
provenance_date: '2026-11-10'
provider_name: vivioo-io
provider_slug: vivioo-io
slug: vivioo-io-eligibility
source_date: '2026-11-10'
source_filename: vivioo-io-eligibility.yml
source_heading: Eligibility
source_page: https://vivioo.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: vivioo-io\naid: vivioo-io\nurl: https://vivioo.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older, or the age of majority where you live.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You agree to use the Platform lawfully and responsibly.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older, or the age of majority where you live.\n"
source_yaml_url: https://artifacts.apis.io/vivioo-io/eligibility/vivioo-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from vivioo-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Ethics
- Testing
- Privacy
---
