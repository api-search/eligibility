---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'B2B only. The Services are intended for business users (Sv: Näringsidkare) and not for consumers (Sv: Konsumenter).'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Special-category data without legal basis and DPA
    text: '(g) submit special-category/highly sensitive data without a valid legal basis and a written data processing agreement (Sv: Personuppgiftsbiträdesavtal, DPA)'
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
name: Brickanta
provenance_date: '2026-11-09'
provider_name: Brickanta
provider_slug: brickanta
slug: brickanta-eligibility
source_date: '2026-11-09'
source_filename: brickanta-eligibility.yml
source_heading: Eligibility
source_page: https://brickanta.com/terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brickanta\naid: brickanta\nurl: https://brickanta.com/terms.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'B2B only. The Services are intended for business users (Sv: Näringsidkare) and not for consumers (Sv: Konsumenter).'\nrestricted_uses:\n- summary: Special-category data without legal basis and DPA\n  text: '(g) submit special-category/highly sensitive data without a valid legal basis and a written data processing\n    agreement (Sv: Personuppgiftsbiträdesavtal, DPA)'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brickanta/eligibility/brickanta-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Brickanta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Artificial Intelligence
- Construction
- AI Agents
- Procurement
- Compliance
---
