---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms on behalf of a company or other legal entity, you represent and warrant that you have the full legal authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Usage beyond licence scope
    text: You may not use the Platform in excess of the permitted scope.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you will be required to register for an account by creating a username and a password
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coro
provenance_date: '2026-11-09'
provider_name: Coro
provider_slug: coro
slug: coro-eligibility
source_date: '2026-11-09'
source_filename: coro-eligibility.yml
source_heading: Eligibility
source_page: https://www.coro.net/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coro\naid: coro\nurl: https://www.coro.net/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms on behalf of a company or other legal entity, you represent and warrant\n    that you have the full legal authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Usage beyond licence scope\n  text: You may not use the Platform in excess of the permitted scope.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you will be required to register for an account\
  \ by creating a username and a password\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coro/eligibility/coro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Coro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Security
- Endpoint Security
- Email Security
- Cloud Security
- Data Protection
- MSP
- Webhook
- MCP
---
