---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer represents and warrants that Customer is at least eighteen (18) years of age.
    type: individual
  - text: Customer further represents and warrants that Customer is entering into this Agreement for business or professional purposes and not primarily for personal, family, or household use.
    type: business
  minimum_age:
    text: Customer represents and warrants that Customer is at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Competitive product development
    text: use or access the Platform, Documentation, or Content to develop a product or service that is competitive with Company’s products, services, or Platform
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
name: Double
provenance_date: '2026-11-09'
provider_name: Double
provider_slug: double
slug: double-eligibility
source_date: '2026-11-09'
source_filename: double-eligibility.yml
source_heading: Eligibility
source_page: https://withdouble.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Double\naid: double\nurl: https://withdouble.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Customer represents and warrants that Customer is at least eighteen (18) years of age.\n- type: business\n  text: Customer further represents and warrants that Customer is entering into this Agreement for business or professional\n    purposes and not primarily for personal, family, or household use.\nrestricted_uses:\n- summary: Competitive product development\n  text: use or access the Platform, Documentation,\
  \ or Content to develop a product or service that is competitive\n    with Company’s products, services, or Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Customer represents and warrants that Customer is at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/double/eligibility/double-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Double's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Future Of Work
- Executive Assistant
- Virtual Assistant
- Productivity
- Delegation
- AI Assistant
- Remote Work
---
