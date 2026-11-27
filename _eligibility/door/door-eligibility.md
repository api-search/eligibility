---
api_specs:
- filename: door-access-management-api-openapi.yml
  format: yaml
  label: Door Access Management API
  slug: door-access-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-access-management-api-openapi.yml
- filename: door-buildings-api-openapi.yml
  format: yaml
  label: Door Buildings API
  slug: door-buildings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-buildings-api-openapi.yml
- filename: door-doors-and-keys-api-openapi.yml
  format: yaml
  label: Door Doors and Keys API
  slug: door-doors-and-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-doors-and-keys-api-openapi.yml
- filename: door-partner-authentication-api-openapi.yml
  format: yaml
  label: Door Partner Authentication API
  slug: door-partner-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-partner-authentication-api-openapi.yml
- filename: door-user-authentication-api-openapi.yml
  format: yaml
  label: Door User Authentication API
  slug: door-user-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-user-authentication-api-openapi.yml
- filename: door-users-api-openapi.yml
  format: yaml
  label: Door Users API
  slug: door-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Our Products and Services are intended for use in the United States and Canada only.
  entity_types:
  - text: You must be at least 18 years old to register for an account. If you are between thirteen 13 and 18 years old, you may only register for an account and use the Services with the permission and under the supervision of a parent or legal guardian
    type: individual
  - text: If you are accessing and using the Products and Services on behalf of an entity, you represent and warrant that you have the right, authority, and capacity to accept and agree to these terms on behalf of yourself and the entity you represent.
    type: business
  minimum_age:
    text: You must be at least 18 years old to register for an account.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Services only for lawful purposes and in accordance with these Terms.
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
name: Door
provenance_date: '2026-11-09'
provider_name: Door
provider_slug: door
slug: door-eligibility
source_date: '2026-11-09'
source_filename: door-eligibility.yml
source_heading: Eligibility
source_page: https://door.com/policy/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Door\naid: door\nurl: https://door.com/policy/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Our Products and Services are intended for use in the United States and Canada only.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to register for an account. If you are between thirteen 13 and 18 years\n    old, you may only register for an account and use the Services with the permission and under the supervision\n    of a parent or legal guardian\n- type: business\n  text: If you are accessing and using the\
  \ Products and Services on behalf of an entity, you represent and warrant\n    that you have the right, authority, and capacity to accept and agree to these terms on behalf of yourself and\n    the entity you represent.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Services only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register for an account.\n"
source_yaml_url: https://artifacts.apis.io/door/eligibility/door-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Door's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Access Control
- Smart Buildings
- PropTech
- Physical Security
- IoT
- Multifamily
- Real Estate
- Smart Lock
- Building Automation
---
