---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the individual signing the order is entering into the agreement on behalf of a company or other legal entity, such individual represents that such individual has the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful business purpose only
    text: solely for Customer’s lawful business purpose
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
name: SafetyKit
provenance_date: '2026-11-10'
provider_name: SafetyKit
provider_slug: safetykit
slug: safetykit-eligibility
source_date: '2026-11-10'
source_filename: safetykit-eligibility.yml
source_heading: Eligibility
source_page: https://app.safetykit.com/msa_2024-03-25.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SafetyKit\naid: safetykit\nurl: https://app.safetykit.com/msa_2024-03-25.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the individual signing the order is entering into the agreement on behalf of a company or other legal\n    entity, such individual represents that such individual has the authority to bind such entity\nrestricted_uses:\n- summary: Lawful business purpose only\n  text: solely for Customer’s lawful business purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/safetykit/eligibility/safetykit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from SafetyKit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Trust and Safety
- Fraud Prevention
- Content Moderation
- Risk Management
- AI Agents
- Compliance
---
