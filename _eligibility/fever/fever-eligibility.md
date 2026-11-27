---
api_specs:
- filename: fever-authentication-api-openapi.yml
  format: yaml
  label: Fever Authentication API
  slug: fever-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-authentication-api-openapi.yml
- filename: fever-feverzone-api-openapi.yml
  format: yaml
  label: Fever FeverZone API
  slug: fever-feverzone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-feverzone-api-openapi.yml
- filename: fever-order-items-api-openapi.yml
  format: yaml
  label: Fever Order Items API
  slug: fever-order-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-order-items-api-openapi.yml
- filename: fever-plans-api-openapi.yml
  format: yaml
  label: Fever Plans API
  slug: fever-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-plans-api-openapi.yml
- filename: fever-sessions-api-openapi.yml
  format: yaml
  label: Fever Sessions API
  slug: fever-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-sessions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Section 5.1 restricts users located in Restricted Countries including Cuba, Iran, North Korea, Sudan or Syria.
  entity_types:
  - text: you must be at least eighteen (18) years of age, or the legal age of majority where you reside, to use the Services
    type: individual
  - text: If you will be using the Services on behalf of an entity, you agree to these Terms of Service on behalf of that entity and its affiliates
    type: business
  minimum_age:
    text: you must be at least eighteen (18) years of age, or the legal age of majority where you reside, to use the Services. Otherwise you may use the Services only with the involvement of a parent or guardian. In any event, you may not use the Services or register if you are under the age of thirteen (13).
    value: '18'
  restricted_uses:
  - summary: No resale or speculative use of accounts
    text: using any Fever account for resale or for speculative, false, fraudulent or any other purpose not expressly permitted by these Terms of Use
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
name: Fever
provenance_date: '2026-11-09'
provider_name: Fever
provider_slug: fever
slug: fever-eligibility
source_date: '2026-11-09'
source_filename: fever-eligibility.yml
source_heading: Eligibility
source_page: https://feverup.com/legal/terms_en.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fever\naid: fever\nurl: https://feverup.com/legal/terms_en.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Section 5.1 restricts users located in Restricted Countries including Cuba, Iran, North Korea, Sudan or\n    Syria.\nentity_types:\n- type: individual\n  text: you must be at least eighteen (18) years of age, or the legal age of majority where you reside, to use the\n    Services\n- type: business\n  text: If you will be using the Services on behalf of an entity, you agree to these Terms of Service on behalf\n    of that entity and its affiliates\nrestricted_uses:\n\
  - summary: No resale or speculative use of accounts\n  text: using any Fever account for resale or for speculative, false, fraudulent or any other purpose not expressly\n    permitted by these Terms of Use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least eighteen (18) years of age, or the legal age of majority where you reside, to use the\n    Services. Otherwise you may use the Services only with the involvement of a parent or guardian. In any event,\n    you may not use the Services or register if you are under the age of thirteen (13).\n"
source_yaml_url: https://artifacts.apis.io/fever/eligibility/fever-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Fever's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Live Entertainment
- Event
- Ticketing
- Experience
- Reporting
- MCP
---
