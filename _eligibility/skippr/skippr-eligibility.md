---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To create an account and use the Services as a Client, you must be at least 18 years old and able to form a binding contract.
    type: individual
  - text: 'Client : The individual or organization that holds a Skippr account and workspace.'
    type: business
  minimum_age:
    text: you must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Special category and sensitive data
    text: Do not capture secrets (e.g., credentials) or special-category/sensitive data (such as health information); the Services are not intended for such data.
  - summary: Targeting minors
    text: Targets minors under the age of 13 (or the applicable age of consent in relevant jurisdictions).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may verify the identity and eligibility of account holders, and may refuse, limit, or condition account or workspace creation
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Skippr
provenance_date: '2026-11-10'
provider_name: Skippr
provider_slug: skippr
slug: skippr-eligibility
source_date: '2026-11-10'
source_filename: skippr-eligibility.yml
source_heading: Eligibility
source_page: https://www.skippr.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skippr\naid: skippr\nurl: https://www.skippr.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To create an account and use the Services as a Client, you must be at least 18 years old and able to form\n    a binding contract.\n- type: business\n  text: 'Client : The individual or organization that holds a Skippr account and workspace.'\nrestricted_uses:\n- summary: Special category and sensitive data\n  text: Do not capture secrets (e.g., credentials) or special-category/sensitive data (such as health information);\n    the\
  \ Services are not intended for such data.\n- summary: Targeting minors\n  text: Targets minors under the age of 13 (or the applicable age of consent in relevant jurisdictions).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may verify the identity and eligibility of account holders, and may refuse, limit, or condition account\n    or workspace creation\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/skippr/eligibility/skippr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Skippr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Voice Agents
- Developer Tools
- MCP
- SDK
- Product Analytics
- Accessibility
---
