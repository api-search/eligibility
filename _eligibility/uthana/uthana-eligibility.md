---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 to create an Account or act as an Authorized User.
    type: individual
  - text: If you act for an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 to create an Account or act as an Authorized User.
    value: '18'
  restricted_uses:
  - summary: AI-training dataset resale
    text: You may not sell, license, or distribute Customer Outputs as AI-training datasets without a separate written agreement with Uthana.
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
name: Uthana
provenance_date: '2026-11-10'
provider_name: Uthana
provider_slug: uthana
slug: uthana-eligibility
source_date: '2026-11-10'
source_filename: uthana-eligibility.yml
source_heading: Eligibility
source_page: https://uthana.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uthana\naid: uthana\nurl: https://uthana.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 to create an Account or act as an Authorized User.\n- type: business\n  text: If you act for an organization, you represent that you have authority to bind that organization.\nrestricted_uses:\n- summary: AI-training dataset resale\n  text: You may not sell, license, or distribute Customer Outputs as AI-training datasets without a separate written\n    agreement with Uthana.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 to create an Account or act as an Authorized User.\n"
source_yaml_url: https://artifacts.apis.io/uthana/eligibility/uthana-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Uthana's own page on 2026-11-10.
synthetic: false
tags:
- Animation
- 3D Characters
- Generative AI
- Motion Capture
- Gaming
- Robotics
- Foundation Models
- GraphQL
---
