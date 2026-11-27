---
api_specs:
- filename: guidewire-integration-gateway-asyncapi.yml
  format: yaml
  label: Guidewire Integration Gateway API
  slug: guidewire-integration-gateway-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/guidewire/asyncapi/guidewire-integration-gateway-asyncapi.yml
- filename: guidewire-accounts-api-openapi.yml
  format: yaml
  label: Guidewire Accounts API
  slug: guidewire-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-accounts-api-openapi.yml
- filename: guidewire-claims-api-openapi.yml
  format: yaml
  label: Guidewire Claims API
  slug: guidewire-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-claims-api-openapi.yml
- filename: guidewire-exposures-api-openapi.yml
  format: yaml
  label: Guidewire Exposures API
  slug: guidewire-exposures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-exposures-api-openapi.yml
- filename: guidewire-fnol-api-openapi.yml
  format: yaml
  label: Guidewire FNOL API
  slug: guidewire-fnol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-fnol-api-openapi.yml
- filename: guidewire-payments-api-openapi.yml
  format: yaml
  label: Guidewire Payments API
  slug: guidewire-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-payments-api-openapi.yml
- filename: guidewire-policies-api-openapi.yml
  format: yaml
  label: Guidewire Policies API
  slug: guidewire-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-policies-api-openapi.yml
- filename: guidewire-quotes-api-openapi.yml
  format: yaml
  label: Guidewire Quotes API
  slug: guidewire-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-quotes-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competitive development using site
    text: to directly or indirectly develop, promote, distribute, sell or support any product or service that is competitive with Guidewire’s products and services
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
name: Guidewire
provenance_date: '2026-11-09'
provider_name: Guidewire
provider_slug: guidewire
slug: guidewire-eligibility
source_date: '2026-11-09'
source_filename: guidewire-eligibility.yml
source_heading: Eligibility
source_page: https://www.guidewire.com/legal-notices
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Guidewire\naid: guidewire\nurl: https://www.guidewire.com/legal-notices\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No competitive development using site\n  text: to directly or indirectly develop, promote, distribute, sell or support any product or service that is competitive\n    with Guidewire’s products and services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/guidewire/eligibility/guidewire-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Guidewire's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Policy
- Claims
- Billing
- Property and Casualty
---
