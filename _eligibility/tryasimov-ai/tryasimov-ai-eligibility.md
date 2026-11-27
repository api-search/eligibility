---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: participating from an allowed launch country/region
  entity_types:
  - text: You must be at least 18 years old, legally able to enter this agreement
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Recording without permission or of minors
    text: You must have permission to record in the location and must avoid private documents, screens, credentials, private conversations, bystanders without permission, minors unless explicitly allowed, and restricted or confidential facilities.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Asimov may require account verification, profile setup, consent acceptance, device enrollment, and payout onboarding before assigning work or paying accepted sessions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Asimov
provenance_date: '2026-11-10'
provider_name: Asimov
provider_slug: tryasimov-ai
slug: tryasimov-ai-eligibility
source_date: '2026-11-10'
source_filename: tryasimov-ai-eligibility.yml
source_heading: Eligibility
source_page: https://tryasimov.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asimov\naid: tryasimov-ai\nurl: https://tryasimov.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: participating from an allowed launch country/region\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, legally able to enter this agreement\nrestricted_uses:\n- summary: Recording without permission or of minors\n  text: You must have permission to record in the location and must avoid private documents, screens, credentials,\n    private conversations, bystanders without permission, minors unless explicitly allowed, and restricted or confidential\n\
  \    facilities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Asimov may require account verification, profile setup, consent acceptance, device enrollment, and payout\n    onboarding before assigning work or paying accepted sessions.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/tryasimov-ai/eligibility/tryasimov-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Asimov's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Data
- Artificial Intelligence
- Human Intelligence
---
