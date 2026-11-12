---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and give accurate account information.
    type: individual
  minimum_age:
    text: You must be at least 18 and give accurate account information.
    value: '18'
  restricted_uses:
  - summary: Not professional advice
    text: The service is a research aid, not professional, medical or legal advice; check important findings in the original sources.
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
name: Corroborum
provenance_date: '2026-11-09'
provider_name: Corroborum
provider_slug: corroborum-com
slug: corroborum-com-eligibility
source_date: '2026-11-09'
source_filename: corroborum-com-eligibility.yml
source_heading: Eligibility
source_page: https://corroborum.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corroborum\naid: corroborum-com\nurl: https://corroborum.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and give accurate account information.\nrestricted_uses:\n- summary: Not professional advice\n  text: The service is a research aid, not professional, medical or legal advice; check important findings in the\n    original sources.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and give accurate account\
  \ information.\n"
source_yaml_url: https://artifacts.apis.io/corroborum-com/eligibility/corroborum-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Corroborum's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Academic Research
- Literature Search
- Scholarly Papers
- MCP
- AI Assistants
- Citations
---
