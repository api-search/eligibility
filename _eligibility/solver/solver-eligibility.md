---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for use by small and medium-sized businesses ("SMBs") and their authorized users.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have the authority to enter into agreements on behalf of your business to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: Not using the Service for any illegal or unauthorized purpose.
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
name: Solver
provenance_date: '2026-11-10'
provider_name: Solver
provider_slug: solver
slug: solver-eligibility
source_date: '2026-11-10'
source_filename: solver-eligibility.yml
source_heading: Eligibility
source_page: https://solver.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Solver\naid: solver\nurl: https://solver.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for use by small and medium-sized businesses (\"SMBs\") and their authorized users.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: Not using the Service for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have the authority to enter into agreements\
  \ on behalf of your business\n    to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/solver/eligibility/solver-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Solver's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Marketing
- E-Commerce
- Automation
---
