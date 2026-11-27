---
api_specs:
- filename: recallsapi-com-account-api-openapi.yml
  format: yaml
  label: recallsapi-com Account API
  slug: recallsapi-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-account-api-openapi.yml
- filename: recallsapi-com-alerts-api-openapi.yml
  format: yaml
  label: recallsapi-com Alerts API
  slug: recallsapi-com-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-alerts-api-openapi.yml
- filename: recallsapi-com-billing-api-openapi.yml
  format: yaml
  label: recallsapi-com Billing API
  slug: recallsapi-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-billing-api-openapi.yml
- filename: recallsapi-com-catalogs-api-openapi.yml
  format: yaml
  label: recallsapi-com Catalogs API
  slug: recallsapi-com-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-catalogs-api-openapi.yml
- filename: recallsapi-com-check-api-openapi.yml
  format: yaml
  label: recallsapi-com Check API
  slug: recallsapi-com-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-check-api-openapi.yml
- filename: recallsapi-com-credits-api-openapi.yml
  format: yaml
  label: recallsapi-com Credits API
  slug: recallsapi-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-credits-api-openapi.yml
- filename: recallsapi-com-health-api-openapi.yml
  format: yaml
  label: recallsapi-com Health API
  slug: recallsapi-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-health-api-openapi.yml
- filename: recallsapi-com-keys-api-openapi.yml
  format: yaml
  label: recallsapi-com Keys API
  slug: recallsapi-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-keys-api-openapi.yml
- filename: recallsapi-com-mcp-api-openapi.yml
  format: yaml
  label: recallsapi-com MCP API
  slug: recallsapi-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-mcp-api-openapi.yml
- filename: recallsapi-com-recalls-api-openapi.yml
  format: yaml
  label: recallsapi-com Recalls API
  slug: recallsapi-com-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-recalls-api-openapi.yml
- filename: recallsapi-com-receipts-api-openapi.yml
  format: yaml
  label: recallsapi-com Receipts API
  slug: recallsapi-com-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-receipts-api-openapi.yml
- filename: recallsapi-com-signals-api-openapi.yml
  format: yaml
  label: recallsapi-com Signals API
  slug: recallsapi-com-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-signals-api-openapi.yml
- filename: recallsapi-com-vehicles-api-openapi.yml
  format: yaml
  label: recallsapi-com Vehicles API
  slug: recallsapi-com-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-vehicles-api-openapi.yml
- filename: recallsapi-com-well-known-api-openapi.yml
  format: yaml
  label: recallsapi-com .well Known API
  slug: recallsapi-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-well-known-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use the service from, or on behalf of anyone in, a country or region under comprehensive US sanctions.
  entity_types:
  - text: You must be at least 18 years old and able to enter a binding contract to use the service.
    type: individual
  - text: If you use the service for an organization, you accept these terms for it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter a binding contract to use the service.
    value: '18'
  restricted_uses:
  - summary: Consumer reports and eligibility decisions
    text: Use the service or its data as a consumer report, or to make or support decisions about any individual's eligibility for credit, insurance, employment, housing or any other purpose covered by the Fair Credit Reporting Act or similar laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You get an API key by giving a valid email address; we send the key to that address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: recallsapi-com
provenance_date: '2026-11-10'
provider_name: recallsapi-com
provider_slug: recallsapi-com
slug: recallsapi-com-eligibility
source_date: '2026-11-10'
source_filename: recallsapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://recallsapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: recallsapi-com\naid: recallsapi-com\nurl: https://recallsapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use the service from, or on behalf of anyone in, a country or region under comprehensive US sanctions.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter a binding contract to use the service.\n- type: business\n  text: If you use the service for an organization, you accept these terms for it.\nrestricted_uses:\n- summary: Consumer reports and eligibility decisions\n  text: Use the service or its data as a consumer report,\
  \ or to make or support decisions about any individual's\n    eligibility for credit, insurance, employment, housing or any other purpose covered by the Fair Credit Reporting\n    Act or similar laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You get an API key by giving a valid email address; we send the key to that address.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter a binding contract to use the service.\n"
source_yaml_url: https://artifacts.apis.io/recallsapi-com/eligibility/recallsapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from recallsapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Recall
- E-Commerce
- Safety
- US-Agencies
---
