---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are prohibited under applicable law from using the Service, then you may not use it.
  entity_types:
  - text: You must be at least 18-years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18-years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal use
    text: use the Service for any illegal purpose or in violation of any local, state, national, or international law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access most features of the Service, you must register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Buffer
provenance_date: '2026-11-09'
provider_name: Buffer
provider_slug: buffer
slug: buffer-eligibility
source_date: '2026-11-09'
source_filename: buffer-eligibility.yml
source_heading: Eligibility
source_page: https://buffer.com/legal#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buffer\naid: buffer\nurl: https://buffer.com/legal#terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you are prohibited under applicable law from using the Service, then you may not use it.\nentity_types:\n- type: individual\n  text: You must be at least 18-years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Illegal use\n  text: use the Service\
  \ for any illegal purpose or in violation of any local, state, national, or international\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access most features of the Service, you must register for an account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18-years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/buffer/eligibility/buffer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Buffer's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Scheduling
- Analytics
- Publishing
- Content Management
- Social Media Management
- Social Media Marketing
- Marketing
- Content Scheduling
- GraphQL
- MCP
- Agents
---
