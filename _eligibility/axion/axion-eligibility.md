---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the customer identified in the applicable Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Human oversight required for outputs
    text: use the Platform Outputs without appropriate human oversight or independent managerial or professional judgment
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
name: Axion
provenance_date: '2026-11-09'
provider_name: Axion
provider_slug: axion
slug: axion-eligibility
source_date: '2026-11-09'
source_filename: axion-eligibility.yml
source_heading: Eligibility
source_page: https://www.axion.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Axion\naid: axion\nurl: https://www.axion.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the customer identified in the applicable Order Form\nrestricted_uses:\n- summary: Human oversight required for outputs\n  text: use the Platform Outputs without appropriate human oversight or independent managerial or professional judgment\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/axion/eligibility/axion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Axion's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Manufacturing
- Quality Management
- Warranty
- Root Cause Analysis
- Enterprise Saas
---
