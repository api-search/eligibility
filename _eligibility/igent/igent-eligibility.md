---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If Customer is an individual (non-business user), Customer represents and warrants that: (a) they are of legal age to enter into this Agreement'
    type: individual
  - text: If you are a company or other entity, the individual accepting this Agreement on your behalf represents and warrants that they have authority to bind you to this Agreement.
    type: business
  minimum_age:
    text: they are of legal age to enter into this Agreement
    value: legal age
  restricted_uses:
  - summary: High-risk applications
    text: use our service for high-risk applications, including but not limited to medical advice, financial guidance, legal advice, or any application requiring regulatory approval without explicit approval or additional safety measures
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
name: iGent
provenance_date: '2026-11-09'
provider_name: iGent
provider_slug: igent
slug: igent-eligibility
source_date: '2026-11-09'
source_filename: igent-eligibility.yml
source_heading: Eligibility
source_page: https://igent.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iGent\naid: igent\nurl: https://igent.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'If Customer is an individual (non-business user), Customer represents and warrants that: (a) they are of\n    legal age to enter into this Agreement'\n- type: business\n  text: If you are a company or other entity, the individual accepting this Agreement on your behalf represents\n    and warrants that they have authority to bind you to this Agreement.\nrestricted_uses:\n- summary: High-risk applications\n  text: use our service for high-risk\
  \ applications, including but not limited to medical advice, financial guidance,\n    legal advice, or any application requiring regulatory approval without explicit approval or additional safety\n    measures\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: they are of legal age to enter into this Agreement\n"
source_yaml_url: https://artifacts.apis.io/igent/eligibility/igent-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from iGent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- Artificial Intelligence
- Software Development
- Coding Agents
- Developer Tools
- AI Agents
- Automation
- LLM
- Cloud Sandbox
---
