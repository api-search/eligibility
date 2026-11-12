---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service in violation of US export control or sanctions laws, or from a country or by a person subject to US sanctions.
  entity_types:
  - text: The Service is for businesses; it isn't meant for personal, family or household use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal use
    text: The Service is for businesses; it isn't meant for personal, family or household use.
  - summary: No sensitive data
    text: 'enter data you don''t have the right to share with us, or data the Service isn''t designed for: government ID numbers, bank account or payment card numbers, or health information'
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
name: CompSlate
provenance_date: '2026-11-09'
provider_name: CompSlate
provider_slug: compslate-com
slug: compslate-com-eligibility
source_date: '2026-11-09'
source_filename: compslate-com-eligibility.yml
source_heading: Eligibility
source_page: https://compslate.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CompSlate\naid: compslate-com\nurl: https://compslate.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service in violation of US export control or sanctions laws, or from a country or by\n    a person subject to US sanctions.\nentity_types:\n- type: business\n  text: The Service is for businesses; it isn't meant for personal, family or household use.\nrestricted_uses:\n- summary: No personal use\n  text: The Service is for businesses; it isn't meant for personal, family or household use.\n- summary: No sensitive data\n  text: 'enter data you don''t have\
  \ the right to share with us, or data the Service isn''t designed for: government\n    ID numbers, bank account or payment card numbers, or health information'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/compslate-com/eligibility/compslate-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from CompSlate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales Compensation
- Sales Commissions
- Revenue Operations
- MCP
- AI Assistants
- SaaS
---
