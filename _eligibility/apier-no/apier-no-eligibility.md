---
api_specs:
- filename: apier-no-account-api-openapi.yml
  format: yaml
  label: Apier.no Account API
  slug: apier-no-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-account-api-openapi.yml
- filename: apier-no-actions-api-openapi.yml
  format: yaml
  label: Apier.no Actions API
  slug: apier-no-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-actions-api-openapi.yml
- filename: apier-no-admin-api-openapi.yml
  format: yaml
  label: Apier.no Admin API
  slug: apier-no-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-admin-api-openapi.yml
- filename: apier-no-altinn-api-openapi.yml
  format: yaml
  label: Apier.no Altinn API
  slug: apier-no-altinn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-altinn-api-openapi.yml
- filename: apier-no-auth-gateway-api-openapi.yml
  format: yaml
  label: Apier.no Auth Gateway API
  slug: apier-no-auth-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-auth-gateway-api-openapi.yml
- filename: apier-no-brreg-api-openapi.yml
  format: yaml
  label: Apier.no Brreg API
  slug: apier-no-brreg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-brreg-api-openapi.yml
- filename: apier-no-changes-api-openapi.yml
  format: yaml
  label: Apier.no Changes API
  slug: apier-no-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-changes-api-openapi.yml
- filename: apier-no-company-api-openapi.yml
  format: yaml
  label: Apier.no Company API
  slug: apier-no-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-company-api-openapi.yml
- filename: apier-no-discovery-api-openapi.yml
  format: yaml
  label: Apier.no Discovery API
  slug: apier-no-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-discovery-api-openapi.yml
- filename: apier-no-fullmakt-api-openapi.yml
  format: yaml
  label: Apier.no Fullmakt API
  slug: apier-no-fullmakt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-fullmakt-api-openapi.yml
- filename: apier-no-infrastructure-api-openapi.yml
  format: yaml
  label: Apier.no Infrastructure API
  slug: apier-no-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-infrastructure-api-openapi.yml
- filename: apier-no-knowledge-api-openapi.yml
  format: yaml
  label: Apier.no Knowledge API
  slug: apier-no-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-knowledge-api-openapi.yml
- filename: apier-no-privacy-api-openapi.yml
  format: yaml
  label: Apier.no Privacy API
  slug: apier-no-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-privacy-api-openapi.yml
- filename: apier-no-public-api-openapi.yml
  format: yaml
  label: Apier.no Public API
  slug: apier-no-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-public-api-openapi.yml
- filename: apier-no-sandbox-api-openapi.yml
  format: yaml
  label: Apier.no Sandbox API
  slug: apier-no-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-sandbox-api-openapi.yml
- filename: apier-no-subscriptions-api-openapi.yml
  format: yaml
  label: Apier.no Subscriptions API
  slug: apier-no-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-subscriptions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Apier is intended for professional, business use. You must be of legal age and have the authority to bind the business you represent.
    type: business
  minimum_age:
    text: You must be of legal age and have the authority to bind the business you represent.
    value: legal age
  restricted_uses:
  - summary: False information to authorities
    text: Use data from the service to give false or misleading information to public authorities.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must be of legal age and have the authority to bind the business you represent.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Apier.no
provenance_date: '2026-11-09'
provider_name: Apier.no
provider_slug: apier-no
slug: apier-no-eligibility
source_date: '2026-11-09'
source_filename: apier-no-eligibility.yml
source_heading: Eligibility
source_page: https://www.apier.no/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apier.no\naid: apier-no\nurl: https://www.apier.no/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Apier is intended for professional, business use. You must be of legal age and have the authority to bind\n    the business you represent.\nrestricted_uses:\n- summary: False information to authorities\n  text: Use data from the service to give false or misleading information to public authorities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must be of legal age and have the authority to bind the\
  \ business you represent.\nminimum_age:\n  value: legal age\n  text: You must be of legal age and have the authority to bind the business you represent.\n"
source_yaml_url: https://artifacts.apis.io/apier-no/eligibility/apier-no-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Apier.no's own page on 2026-11-09.
synthetic: false
tags:
- Norwegian
- Company Data
- MCP
- Verification
---
