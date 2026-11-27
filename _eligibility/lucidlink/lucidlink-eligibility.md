---
api_specs:
- filename: lucidlink-billing-api-openapi.yml
  format: yaml
  label: LucidLink Billing API
  slug: lucidlink-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucidlink/openapi/lucidlink-billing-api-openapi.yml
- filename: lucidlink-domain-api-openapi.yml
  format: yaml
  label: LucidLink Domain API
  slug: lucidlink-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucidlink/openapi/lucidlink-domain-api-openapi.yml
- filename: lucidlink-filespace-api-openapi.yml
  format: yaml
  label: LucidLink Filespace API
  slug: lucidlink-filespace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucidlink/openapi/lucidlink-filespace-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are a natural person who is acting for purposes which are outside your trade, business, craft, or profession
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ORGANIZATION OR ENTITY, YOU HAVE FULL AUTHORITY TO BIND THE ORGANIZATION OR ENTITY
    type: business
  minimum_age:
    text: 'YOU REPRESENT AND WARRANT THAT: (i) YOU HAVE REACHED THE FULL LEGAL AGE'
    value: full legal age
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: LucidLink shall accept the Order Form or refuse it within fourteen-(14-) day term upon its receipt
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LucidLink
provenance_date: '2026-11-09'
provider_name: LucidLink
provider_slug: lucidlink
slug: lucidlink-eligibility
source_date: '2026-11-09'
source_filename: lucidlink-eligibility.yml
source_heading: Eligibility
source_page: https://www.lucidlink.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LucidLink\naid: lucidlink\nurl: https://www.lucidlink.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are a natural person who is acting for purposes which are outside your trade, business, craft, or\n    profession\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ORGANIZATION OR ENTITY, YOU HAVE FULL AUTHORITY\n    TO BIND THE ORGANIZATION OR ENTITY\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: LucidLink shall accept the Order Form\
  \ or refuse it within fourteen-(14-) day term upon its receipt\nminimum_age:\n  value: full legal age\n  text: 'YOU REPRESENT AND WARRANT THAT: (i) YOU HAVE REACHED THE FULL LEGAL AGE'\n"
source_yaml_url: https://artifacts.apis.io/lucidlink/eligibility/lucidlink-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from LucidLink's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Storage
- File Streaming
- File Collaboration
- Media and Entertainment
- Object Storage
- Developer Platform
- MCP
- AI Agents
- Zero-Knowledge Encryption
---
