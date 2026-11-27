---
api_specs:
- filename: brewmypdf-com-openapi-generated.yml
  format: yaml
  label: BrewMyPDF API
  slug: brewmypdf-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brewmypdf-com/openapi/_ae-authored/brewmypdf-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service in a country subject to United States embargo, or if you are a person or entity designated on a United States restricted-party list, or in violation of United States export laws.
  entity_types:
  - text: You must be at least 18 years old, or the age of majority where you live, to use the Service.
    type: individual
  - text: If you are accepting on behalf of a company, you confirm you are authorized to bind it, and "you" means that company.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live, to use the Service.
    value: '18'
  restricted_uses:
  - summary: High-risk applications
    text: Do not use it for, or incorporate its output into, aviation, medical devices, clinical decision-making, emergency response, life support, nuclear facilities, weapons systems, or the operation of vehicles or industrial control systems.
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
name: BrewMyPDF
provenance_date: '2026-11-09'
provider_name: BrewMyPDF
provider_slug: brewmypdf-com
slug: brewmypdf-com-eligibility
source_date: '2026-11-09'
source_filename: brewmypdf-com-eligibility.yml
source_heading: Eligibility
source_page: https://brewmypdf.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrewMyPDF\naid: brewmypdf-com\nurl: https://brewmypdf.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service in a country subject to United States embargo, or if you are a person or entity\n    designated on a United States restricted-party list, or in violation of United States export laws.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live, to use the Service.\n- type: business\n  text: If you are accepting on behalf of a company, you confirm you are authorized to bind it, and\
  \ \"you\" means\n    that company.\nrestricted_uses:\n- summary: High-risk applications\n  text: Do not use it for, or incorporate its output into, aviation, medical devices, clinical decision-making,\n    emergency response, life support, nuclear facilities, weapons systems, or the operation of vehicles or industrial\n    control systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/brewmypdf-com/eligibility/brewmypdf-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from BrewMyPDF's own page on 2026-11-09.
synthetic: false
tags:
- PDF Generation
- Visual Editor
- Templates
- MCP
- Embeddings
---
