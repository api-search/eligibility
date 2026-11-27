---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To create an account, you must be at least the age of majority or older in your state or country of residence
    type: individual
  - text: In some cases, an account may be assigned to you by an administrator (“Account Administrator”), such as your employer.
    type: business
  minimum_age:
    text: you must be at least the age of majority or older in your state or country of residence
    value: age of majority
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: Neither the services or products of Reltio nor the underlying information or technology may be downloaded or otherwise provided or made available, either directly or indirectly, into any country subject to U.S. trade sanctions
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: we may require you or your Account Administrator to provide information that we may use to confirm your identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Reltio
provenance_date: '2026-11-10'
provider_name: Reltio
provider_slug: reltio
slug: reltio-eligibility
source_date: '2026-11-10'
source_filename: reltio-eligibility.yml
source_heading: Eligibility
source_page: https://www.reltio.com/reltio-website-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reltio\naid: reltio\nurl: https://www.reltio.com/reltio-website-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To create an account, you must be at least the age of majority or older in your state or country of residence\n- type: business\n  text: In some cases, an account may be assigned to you by an administrator (“Account Administrator”), such as\n    your employer.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: Neither the services or products of Reltio nor the underlying information or technology\
  \ may be downloaded\n    or otherwise provided or made available, either directly or indirectly, into any country subject to U.S. trade\n    sanctions\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: we may require you or your Account Administrator to provide information that we may use to confirm your\n    identity\nminimum_age:\n  value: age of majority\n  text: you must be at least the age of majority or older in your state or country of residence\n"
source_yaml_url: https://artifacts.apis.io/reltio/eligibility/reltio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Reltio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Analytics
- Master Data Management
- MDM
- Entity Resolution
- Data Quality
- Data Integration
- AI Agents
- MCP
- SAP
---
