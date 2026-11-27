---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: neither you nor any User is located in, or a national or resident of, any country or territory subject to comprehensive U.S. sanctions
  entity_types:
  - text: The Service is offered solely for business and commercial purposes and is not intended for personal, family, or household use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Business use only
    text: The Service is offered solely for business and commercial purposes and is not intended for personal, family, or household use.
  - summary: Export control and sanctions
    text: You will comply with all applicable U.S. and foreign export control and sanctions laws and will not export, re-export, or transfer the Service or Documentation to any prohibited country, entity, or individual.
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
name: Diagrid
provenance_date: '2026-11-09'
provider_name: Diagrid
provider_slug: diagrid
slug: diagrid-eligibility
source_date: '2026-11-09'
source_filename: diagrid-eligibility.yml
source_heading: Eligibility
source_page: https://www.diagrid.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diagrid\naid: diagrid\nurl: https://www.diagrid.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: neither you nor any User is located in, or a national or resident of, any country or territory subject to\n    comprehensive U.S. sanctions\nentity_types:\n- type: business\n  text: The Service is offered solely for business and commercial purposes and is not intended for personal, family,\n    or household use.\nrestricted_uses:\n- summary: Business use only\n  text: The Service is offered solely for business and commercial purposes and is not intended for personal,\
  \ family,\n    or household use.\n- summary: Export control and sanctions\n  text: You will comply with all applicable U.S. and foreign export control and sanctions laws and will not export,\n    re-export, or transfer the Service or Documentation to any prohibited country, entity, or individual.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/diagrid/eligibility/diagrid-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Diagrid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- AI Agents
- Durable Execution
- Workflows
- Dapr
- MCP
- Microservices
- Cloud-Native
- Distributed Systems
---
