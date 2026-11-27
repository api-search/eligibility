---
api_specs:
- filename: vitally-accounts-api-openapi.yml
  format: yaml
  label: Vitally Accounts API
  slug: vitally-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vitally/openapi/vitally-accounts-api-openapi.yml
- filename: vitally-admins-api-openapi.yml
  format: yaml
  label: Vitally Admins API
  slug: vitally-admins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vitally/openapi/vitally-admins-api-openapi.yml
- filename: vitally-conversations-api-openapi.yml
  format: yaml
  label: Vitally Conversations API
  slug: vitally-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vitally/openapi/vitally-conversations-api-openapi.yml
- filename: vitally-custom-objects-api-openapi.yml
  format: yaml
  label: Vitally Custom Objects API
  slug: vitally-custom-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vitally/openapi/vitally-custom-objects-api-openapi.yml
- filename: vitally-notes-api-openapi.yml
  format: yaml
  label: Vitally Notes API
  slug: vitally-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vitally/openapi/vitally-notes-api-openapi.yml
- filename: vitally-nps-responses-api-openapi.yml
  format: yaml
  label: Vitally NPS Responses API
  slug: vitally-nps-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vitally/openapi/vitally-nps-responses-api-openapi.yml
- filename: vitally-organizations-api-openapi.yml
  format: yaml
  label: Vitally Organizations API
  slug: vitally-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vitally/openapi/vitally-organizations-api-openapi.yml
- filename: vitally-tasks-api-openapi.yml
  format: yaml
  label: Vitally Tasks API
  slug: vitally-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vitally/openapi/vitally-tasks-api-openapi.yml
- filename: vitally-users-api-openapi.yml
  format: yaml
  label: Vitally Users API
  slug: vitally-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vitally/openapi/vitally-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not be in violation of any embargoes, export controls, or other laws of the United States or other countries having jurisdiction over this Agreement, Vitally, and yourself.
  entity_types:
  - text: You must be 18 years or older and capable of forming a binding contract with Vitally
    type: individual
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to this Agreement.
    type: business
  minimum_age:
    text: You must be 18 years or older and capable of forming a binding contract with Vitally
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You may not use our products for any unlawful purpose, nor may you, in the use of the Service, violate any such laws
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
name: Vitally
provenance_date: '2026-11-10'
provider_name: Vitally
provider_slug: vitally
slug: vitally-eligibility
source_date: '2026-11-10'
source_filename: vitally-eligibility.yml
source_heading: Eligibility
source_page: https://www.vitally.io/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vitally\naid: vitally\nurl: https://www.vitally.io/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not be in violation of any embargoes, export controls, or other laws of the United States or other\n    countries having jurisdiction over this Agreement, Vitally, and yourself.\nentity_types:\n- type: individual\n  text: You must be 18 years or older and capable of forming a binding contract with Vitally\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent\
  \ and warrant that you have the authority to bind that entity to this Agreement.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You may not use our products for any unlawful purpose, nor may you, in the use of the Service, violate any\n    such laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older and capable of forming a binding contract with Vitally\n"
source_yaml_url: https://artifacts.apis.io/vitally/eligibility/vitally-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vitally's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Customer Success
- Software-as-a-Service
- CRM
- NPS
- Surveys
- Analytics
- Artificial Intelligence
---
