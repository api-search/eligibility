---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for users who are 18 years or older and capable of forming a binding contract with Brevian.
    type: individual
  minimum_age:
    text: The Site is intended for users who are 18 years or older
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Certain features of the Site may require account creation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brevian
provenance_date: '2026-11-09'
provider_name: Brevian
provider_slug: brevian
slug: brevian-eligibility
source_date: '2026-11-09'
source_filename: brevian-eligibility.yml
source_heading: Eligibility
source_page: https://docs.brevian.ai/security/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brevian\naid: brevian\nurl: https://docs.brevian.ai/security/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended for users who are 18 years or older and capable of forming a binding contract with\n    Brevian.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Certain features of the Site may require account creation.\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/brevian/eligibility/brevian-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Brevian's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales
- Revenue Execution
- AI Agents
- CRM
- MCP
- Enterprise
---
