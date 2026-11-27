---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Promptic is offered exclusively to customers acting in the course of their trade, business, or independent profession (entrepreneurs within Section 14 BGB)
    type: business
  - text: and to legal persons under public law.
    type: government
  minimum_age:
    text: You may use Promptic only if you are legally capable of entering into these Terms.
    value: null
  restricted_uses:
  - summary: Sensitive data submission
    text: You must not submit special category data, criminal-offence data, protected health information, payment card numbers, government identifiers, secrets, or other highly sensitive data unless Promptic has expressly agreed to that use in writing.
  - summary: Unlawful surveillance and biometric identification
    text: Use Promptic for unlawful surveillance, biometric identification, social scoring, or other prohibited AI uses.
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
name: Promptic
provenance_date: '2026-11-10'
provider_name: Promptic
provider_slug: promptic
slug: promptic-eligibility
source_date: '2026-11-10'
source_filename: promptic-eligibility.yml
source_heading: Eligibility
source_page: https://promptic.eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Promptic\naid: promptic\nurl: https://promptic.eu/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Promptic is offered exclusively to customers acting in the course of their trade, business, or independent\n    profession (entrepreneurs within Section 14 BGB)\n- type: government\n  text: and to legal persons under public law.\nrestricted_uses:\n- summary: Sensitive data submission\n  text: You must not submit special category data, criminal-offence data, protected health information, payment\n    card numbers, government identifiers,\
  \ secrets, or other highly sensitive data unless Promptic has expressly\n    agreed to that use in writing.\n- summary: Unlawful surveillance and biometric identification\n  text: Use Promptic for unlawful surveillance, biometric identification, social scoring, or other prohibited AI\n    uses.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may use Promptic only if you are legally capable of entering into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/promptic/eligibility/promptic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Promptic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Optimization
- Enterprise
- LLM
---
