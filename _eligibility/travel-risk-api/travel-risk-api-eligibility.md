---
api_specs:
- filename: travel-risk-api-adb-api-openapi.yml
  format: yaml
  label: Travel Risk API Adb API
  slug: travel-risk-api-adb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-adb-api-openapi.yml
- filename: travel-risk-api-auth-api-openapi.yml
  format: yaml
  label: Travel Risk API Auth API
  slug: travel-risk-api-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-auth-api-openapi.yml
- filename: travel-risk-api-billing-api-openapi.yml
  format: yaml
  label: Travel Risk API Billing API
  slug: travel-risk-api-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-billing-api-openapi.yml
- filename: travel-risk-api-ext-api-openapi.yml
  format: yaml
  label: Travel Risk API Ext API
  slug: travel-risk-api-ext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-ext-api-openapi.yml
- filename: travel-risk-api-public-data-api-openapi.yml
  format: yaml
  label: Travel Risk API Public Data API
  slug: travel-risk-api-public-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-public-data-api-openapi.yml
- filename: travel-risk-api-system-api-openapi.yml
  format: yaml
  label: Travel Risk API System API
  slug: travel-risk-api-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-system-api-openapi.yml
- filename: travel-risk-api-usage-api-openapi.yml
  format: yaml
  label: Travel Risk API Usage API
  slug: travel-risk-api-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organisation, you confirm that you are authorised to bind it, and "you" includes that organisation.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and export compliance
    text: in breach of applicable sanctions and export laws
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
name: Travel Risk API
provenance_date: '2026-11-10'
provider_name: Travel Risk API
provider_slug: travel-risk-api
slug: travel-risk-api-eligibility
source_date: '2026-11-10'
source_filename: travel-risk-api-eligibility.yml
source_heading: Eligibility
source_page: https://travelriskapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Travel Risk API\naid: travel-risk-api\nurl: https://travelriskapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organisation, you confirm that you are authorised to bind it, and\n    \"you\" includes that organisation.\nrestricted_uses:\n- summary: Sanctions and export compliance\n  text: in breach of applicable sanctions and export laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/travel-risk-api/eligibility/travel-risk-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Travel Risk API's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Travel Risk
- Travel Advisories
- Aviation
- Airports
- Risk Scoring
- Safety
- Disaster Alerts
---
