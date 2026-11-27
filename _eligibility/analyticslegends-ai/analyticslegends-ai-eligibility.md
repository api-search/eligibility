---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are a consumer if you act for purposes outside your trade or profession (for instance an employee subscribing privately, or a student)
    type: individual
  - text: you are a professional otherwise (freelancer, firm, company, AI agent operated for a professional account)
    type: business
  minimum_age:
    text: You must be 18 or older.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons or uses
    text: The service is not offered to persons or entities targeted by restrictive measures (sanctions) of the European Union, the United Nations, the United Kingdom or the United States
  - summary: No natural person or personal data via MCP
    text: No natural person and no personal data is served through this channel, at any tier.
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
name: Analytics Legends
provenance_date: '2026-11-09'
provider_name: Analytics Legends
provider_slug: analyticslegends-ai
slug: analyticslegends-ai-eligibility
source_date: '2026-11-09'
source_filename: analyticslegends-ai-eligibility.yml
source_heading: Eligibility
source_page: https://analyticslegends.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Analytics Legends\naid: analyticslegends-ai\nurl: https://analyticslegends.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are a consumer if you act for purposes outside your trade or profession (for instance an employee subscribing\n    privately, or a student)\n- type: business\n  text: you are a professional otherwise (freelancer, firm, company, AI agent operated for a professional account)\nrestricted_uses:\n- summary: Sanctioned persons or uses\n  text: The service is not offered to persons or entities targeted by\
  \ restrictive measures (sanctions) of the European\n    Union, the United Nations, the United Kingdom or the United States\n- summary: No natural person or personal data via MCP\n  text: No natural person and no personal data is served through this channel, at any tier.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/analyticslegends-ai/eligibility/analyticslegends-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Analytics Legends's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- SAP
- Artificial Intelligence
- Data
- Platform
---
