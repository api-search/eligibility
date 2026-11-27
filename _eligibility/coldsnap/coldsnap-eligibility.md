---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: ColdSnap makes no representation that the Service is appropriate, lawful or available in other locations.
  entity_types:
  - text: If you do not agree to be bound by this Agreement, or you are below the age of majority where you are located, you are not permitted to use the Service.
    type: individual
  - text: If you are accessing the Service on behalf of a legal entity, that entity shall be the user hereunder
    type: business
  minimum_age:
    text: you are below the age of majority where you are located, you are not permitted to use the Service
    value: age of majority
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: In certain instances ColdSnap or its vendors may require you to provide proof of identity to access or use the Service, and you agree that you may be denied access or use of the Service if you refuse to provide proof of identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ColdSnap
provenance_date: '2026-11-09'
provider_name: ColdSnap
provider_slug: coldsnap
slug: coldsnap-eligibility
source_date: '2026-11-09'
source_filename: coldsnap-eligibility.yml
source_heading: Eligibility
source_page: https://coldsnap.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ColdSnap\naid: coldsnap\nurl: https://coldsnap.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: ColdSnap makes no representation that the Service is appropriate, lawful or available in other locations.\nentity_types:\n- type: individual\n  text: If you do not agree to be bound by this Agreement, or you are below the age of majority where you are located,\n    you are not permitted to use the Service.\n- type: business\n  text: If you are accessing the Service on behalf of a legal entity, that entity shall be the user hereunder\nrestricted_uses: []\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: false\n  text: In certain instances ColdSnap or its vendors may require you to provide proof of identity to access or use\n    the Service, and you agree that you may be denied access or use of the Service if you refuse to provide proof\n    of identity.\nminimum_age:\n  value: age of majority\n  text: you are below the age of majority where you are located, you are not permitted to use the Service\n"
source_yaml_url: https://artifacts.apis.io/coldsnap/eligibility/coldsnap-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from ColdSnap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Retail
- Food and Beverage
- Consumer Products
- Hardware
- Appliances
- Food Service
- Agentic Commerce
- Shopify
- GraphQL
- MCP
- Universal Commerce Protocol
---
