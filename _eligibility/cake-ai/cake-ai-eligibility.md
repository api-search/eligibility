---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual, your own personal use
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services
    value: '13'
  restricted_uses:
  - summary: Automated decisions and profiling with AI Features
    text: (iv) for the purpose of “automated decision making” or “profiling”
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
name: Cake
provenance_date: '2026-11-09'
provider_name: Cake
provider_slug: cake-ai
slug: cake-ai-eligibility
source_date: '2026-11-09'
source_filename: cake-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.cake.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cake\naid: cake-ai\nurl: https://www.cake.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual, your own personal use\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Automated decisions and profiling with AI Features\n  text: (iv) for the purpose of “automated decision making” or “profiling”\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services\n"
source_yaml_url: https://artifacts.apis.io/cake-ai/eligibility/cake-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cake's own page on 2026-11-09.
synthetic: false
tags:
- AI Platform
- Regulated Industries
- Coding Agents
- Data Extraction
- Enterprise AI
- Governance
- Security
---
