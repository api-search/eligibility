---
api_specs:
- filename: swagger-codegen-clients-api-openapi.yml
  format: yaml
  label: Swagger Codegen Clients API
  slug: swagger-codegen-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swagger-codegen/openapi/swagger-codegen-clients-api-openapi.yml
- filename: swagger-codegen-documentation-api-openapi.yml
  format: yaml
  label: Swagger Codegen Documentation API
  slug: swagger-codegen-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swagger-codegen/openapi/swagger-codegen-documentation-api-openapi.yml
- filename: swagger-codegen-servers-api-openapi.yml
  format: yaml
  label: Swagger Codegen Servers API
  slug: swagger-codegen-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swagger-codegen/openapi/swagger-codegen-servers-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the individual accepting this Agreement does so on behalf of a company or other entity, that individual represents and warrants that they have the legal authority to bind such entity to this Agreement.
    type: business
  - text: If Customer is a U.S. federal government department or agency or contracting on behalf of such department or agency
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No regulated or sensitive data
    text: Customer and its Users may only upload non-production, non-personal, non-sensitive data (e.g., synthetic or dummy data) when using the Solutions.
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
name: Swagger Codegen
provenance_date: '2026-11-10'
provider_name: Swagger Codegen
provider_slug: swagger-codegen
slug: swagger-codegen-eligibility
source_date: '2026-11-10'
source_filename: swagger-codegen-eligibility.yml
source_heading: Eligibility
source_page: https://smartbear.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Swagger Codegen\naid: swagger-codegen\nurl: https://smartbear.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the individual accepting this Agreement does so on behalf of a company or other entity, that individual\n    represents and warrants that they have the legal authority to bind such entity to this Agreement.\n- type: government\n  text: If Customer is a U.S. federal government department or agency or contracting on behalf of such department\n    or agency\nrestricted_uses:\n- summary: No regulated or sensitive\
  \ data\n  text: Customer and its Users may only upload non-production, non-personal, non-sensitive data (e.g., synthetic\n    or dummy data) when using the Solutions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/swagger-codegen/eligibility/swagger-codegen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Swagger Codegen's own page on 2026-11-10.
synthetic: false
tags:
- Client Library
- Code Generation
- Open Source
- OpenAPI
- SDK
- SDK Generation
---
