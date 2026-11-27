---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Service in any capacity, you must be at least the minimum age of digital consent in your country of residence (for example, 13 in the United States and the United Kingdom, and 16 in certain other jurisdictions).
    type: individual
  minimum_age:
    text: To use the Service in any capacity, you must be at least the minimum age of digital consent in your country of residence (for example, 13 in the United States and the United Kingdom, and 16 in certain other jurisdictions).
    value: '13'
  restricted_uses:
  - summary: Individual AI creation limits
    text: As a Professional, you may create a Individual AI only of (a) yourself, or (b) an individual who has provided explicit, informed consent to the creation and intended use of such Individual AI.
  - summary: Prohibited output uses
    text: political purposes, including political campaigning or lobbying
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Monetization access is not automatic and may be approved, suspended, or revoked at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Uare.ai
provenance_date: '2026-11-10'
provider_name: Uare.ai
provider_slug: uare-ai
slug: uare-ai-eligibility
source_date: '2026-11-10'
source_filename: uare-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.uare.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uare.ai\naid: uare-ai\nurl: https://www.uare.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Service in any capacity, you must be at least the minimum age of digital consent in your country\n    of residence (for example, 13 in the United States and the United Kingdom, and 16 in certain other jurisdictions).\nrestricted_uses:\n- summary: Individual AI creation limits\n  text: As a Professional, you may create a Individual AI only of (a) yourself, or (b) an individual who has provided\n\
  \    explicit, informed consent to the creation and intended use of such Individual AI.\n- summary: Prohibited output uses\n  text: political purposes, including political campaigning or lobbying\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Monetization access is not automatic and may be approved, suspended, or revoked at any time.\nminimum_age:\n  value: '13'\n  text: To use the Service in any capacity, you must be at least the minimum age of digital consent in your country\n    of residence (for example, 13 in the United States and the United Kingdom, and 16 in certain other jurisdictions).\n"
source_yaml_url: https://artifacts.apis.io/uare-ai/eligibility/uare-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Uare.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Personal AI
- Digital Twin
- Consumer
- Voice
- MCP
---
