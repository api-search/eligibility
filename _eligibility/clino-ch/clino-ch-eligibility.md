---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: private individuals who employ domestic workers
    type: individual
  - text: sole proprietorships, general and limited partnerships, associations and foundations. The Service is not intended for a company limited by shares (AG), a limited liability company (GmbH) or a cooperative itself
    type: business
  minimum_age:
    text: null
    value: null
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
name: Clino
provenance_date: '2026-11-09'
provider_name: Clino
provider_slug: clino-ch
slug: clino-ch-eligibility
source_date: '2026-11-09'
source_filename: clino-ch-eligibility.yml
source_heading: Eligibility
source_page: https://clino.ch/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clino\naid: clino-ch\nurl: https://clino.ch/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: private individuals who employ domestic workers\n- type: business\n  text: sole proprietorships, general and limited partnerships, associations and foundations. The Service is not\n    intended for a company limited by shares (AG), a limited liability company (GmbH) or a cooperative itself\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clino-ch/eligibility/clino-ch-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Clino's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payroll
- Household Employment
- Domestic Workers
- Social Security
- Switzerland
- HR
- MCP
---
