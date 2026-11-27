---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity executing one or more Order Forms for the Ambient Service
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk applications
    text: THE AMBIENT SERVICE IS NOT DESIGNED OR INTENDED FOR USE IN APPLICATIONS
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
name: Ambient.ai
provenance_date: '2026-11-09'
provider_name: Ambient.ai
provider_slug: ambientai
slug: ambientai-eligibility
source_date: '2026-11-09'
source_filename: ambientai-eligibility.yml
source_heading: Eligibility
source_page: https://www.ambient.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ambient.ai\naid: ambientai\nurl: https://www.ambient.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity executing one or more Order Forms for the Ambient Service\nrestricted_uses:\n- summary: High-risk applications\n  text: THE AMBIENT SERVICE IS NOT DESIGNED OR INTENDED FOR USE IN APPLICATIONS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ambientai/eligibility/ambientai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Ambient.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Physical Security
- Computer Vision
- Artificial Intelligence
- Video Analytics
- Access Control
- Threat Detection
- Enterprise Security
- AI Agents
---
