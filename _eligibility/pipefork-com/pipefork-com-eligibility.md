---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For business, professional, development, and commercial users
    type: business
  - text: If you use only a free, beta, preview, evaluation, or trial plan
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create a Pipefork account or access a Pipefork workspace, including through an invitation.
    value: '18'
  restricted_uses:
  - summary: High-risk and consumer uses
    text: The Service is not intended for consumer, household, medical, emergency, life-critical, safety-critical, financial trading, nuclear, aviation, or other high-risk use cases.
  - summary: Sensitive data uploads
    text: upload or process special categories of personal data, criminal offence data, health data, payment card data, national identification numbers, children's data, or other highly sensitive data unless Pipefork has expressly approved that use in writing
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
name: pipefork-com
provenance_date: '2026-11-10'
provider_name: pipefork-com
provider_slug: pipefork-com
slug: pipefork-com-eligibility
source_date: '2026-11-10'
source_filename: pipefork-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.pipefork.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pipefork-com\naid: pipefork-com\nurl: https://www.pipefork.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: For business, professional, development, and commercial users\n- type: individual\n  text: If you use only a free, beta, preview, evaluation, or trial plan\nrestricted_uses:\n- summary: High-risk and consumer uses\n  text: The Service is not intended for consumer, household, medical, emergency, life-critical, safety-critical,\n    financial trading, nuclear, aviation, or other high-risk use cases.\n- summary: Sensitive\
  \ data uploads\n  text: upload or process special categories of personal data, criminal offence data, health data, payment card\n    data, national identification numbers, children's data, or other highly sensitive data unless Pipefork has expressly\n    approved that use in writing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create a Pipefork account or access a Pipefork workspace, including\n    through an invitation.\n"
source_yaml_url: https://artifacts.apis.io/pipefork-com/eligibility/pipefork-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from pipefork-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- API Builder
- Artificial Intelligence
- MCP
- Low-Code
- Integration
---
