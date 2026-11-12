---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your jurisdiction if that is higher, to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction if that is higher, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Harmful to minors
    text: Use the Service in any way that could harm minors.
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
name: Conduit Mail
provenance_date: '2026-11-09'
provider_name: Conduit Mail
provider_slug: conduitmail-app
slug: conduitmail-app-eligibility
source_date: '2026-11-09'
source_filename: conduitmail-app-eligibility.yml
source_heading: Eligibility
source_page: https://conduitmail.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conduit Mail\naid: conduitmail-app\nurl: https://conduitmail.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction if that is higher, to use\n    the Service.\nrestricted_uses:\n- summary: Harmful to minors\n  text: Use the Service in any way that could harm minors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction\
  \ if that is higher, to use\n    the Service.\n"
source_yaml_url: https://artifacts.apis.io/conduitmail-app/eligibility/conduitmail-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Conduit Mail's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Email Client
- Artificial Intelligence
- MCP
- AI Agents
- Productivity
- Automation
---
