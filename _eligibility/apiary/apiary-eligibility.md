---
api_specs:
- filename: apiary-api-list-api-openapi.yml
  format: yaml
  label: Apiary API List API
  slug: apiary-api-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apiary/openapi/apiary-api-list-api-openapi.yml
- filename: apiary-authentication-api-openapi.yml
  format: yaml
  label: Apiary Authentication API
  slug: apiary-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apiary/openapi/apiary-authentication-api-openapi.yml
- filename: apiary-blueprint-api-openapi.yml
  format: yaml
  label: Apiary Blueprint API
  slug: apiary-blueprint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apiary/openapi/apiary-blueprint-api-openapi.yml
- filename: apiary-user-information-api-openapi.yml
  format: yaml
  label: Apiary User Information API
  slug: apiary-user-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apiary/openapi/apiary-user-information-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years old and have the legal capacity to be bound by these Terms
    type: individual
  - text: If you are accepting these Terms on behalf of a company, you represent that you have the necessary authority to bind such company to these Terms
    type: business
  minimum_age:
    text: You are at least 18 years old and have the legal capacity to be bound by these Terms
    value: '18'
  restricted_uses:
  - summary: Violation of applicable laws
    text: use the Service in violation of applicable laws, rules, and regulations
  - summary: Harmful or abusive use
    text: use the Service to harass any person; cause damage or injury to any person or property
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
name: Apiary
provenance_date: '2026-11-09'
provider_name: Apiary
provider_slug: apiary
slug: apiary-eligibility
source_date: '2026-11-09'
source_filename: apiary-eligibility.yml
source_heading: Eligibility
source_page: https://apiary.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apiary\naid: apiary\nurl: https://apiary.io/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years old and have the legal capacity to be bound by these Terms\n- type: business\n  text: If you are accepting these Terms on behalf of a company, you represent that you have the necessary authority\n    to bind such company to these Terms\nrestricted_uses:\n- summary: Violation of applicable laws\n  text: use the Service in violation of applicable laws, rules, and regulations\n- summary: Harmful or abusive use\n  text:\
  \ use the Service to harass any person; cause damage or injury to any person or property\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old and have the legal capacity to be bound by these Terms\n"
source_yaml_url: https://artifacts.apis.io/apiary/eligibility/apiary-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Apiary's own page on 2026-11-09.
synthetic: false
tags:
- API Blueprint
- API Design
- API Testing
- Collaboration
- Design-First
- Documentation
- Mock Servers
- Oracle
---
