---
api_specs:
- filename: beyond-pricing-accounts-api-openapi.yml
  format: yaml
  label: Beyond Pricing Accounts API
  slug: beyond-pricing-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-accounts-api-openapi.yml
- filename: beyond-pricing-compsets-api-openapi.yml
  format: yaml
  label: Beyond Pricing Compsets API
  slug: beyond-pricing-compsets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-compsets-api-openapi.yml
- filename: beyond-pricing-customizations-api-openapi.yml
  format: yaml
  label: Beyond Pricing Customizations API
  slug: beyond-pricing-customizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-customizations-api-openapi.yml
- filename: beyond-pricing-insights-api-openapi.yml
  format: yaml
  label: Beyond Pricing Insights API
  slug: beyond-pricing-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-insights-api-openapi.yml
- filename: beyond-pricing-listings-api-openapi.yml
  format: yaml
  label: Beyond Pricing Listings API
  slug: beyond-pricing-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-listings-api-openapi.yml
- filename: beyond-pricing-users-api-openapi.yml
  format: yaml
  label: Beyond Pricing Users API
  slug: beyond-pricing-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-users-api-openapi.yml
- filename: beyond-pricing-webhooks-api-openapi.yml
  format: yaml
  label: Beyond Pricing Webhooks API
  slug: beyond-pricing-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-webhooks-api-openapi.yml
- filename: beyond-pricing-oauth2-api-openapi.yml
  format: yaml
  label: Beyond Pricing O Auth2 API
  slug: beyond-pricing-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-oauth2-api-openapi.yml
- filename: beyond-pricing-reservations-api-openapi.yml
  format: yaml
  label: Beyond Pricing Reservations API
  slug: beyond-pricing-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-reservations-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Beyond makes no representations that the Services are appropriate for use in other jurisdictions; users must comply with export laws and not access Services in U.S. embargoed countries or regions.
  entity_types:
  - text: If using the Services on behalf of an organization, User agrees to this Agreement on behalf of that organization and attests that User has the authority to bind that organization to this Agreement.
    type: business
  minimum_age:
    text: must be at least 18 years of age, or the age of legal majority in User's jurisdiction if different than 18.
    value: '18'
  restricted_uses:
  - summary: Illegal or prohibited activity
    text: not use the Services, and ensure that Sub-Users do not use the Services, to engage in illegal or prohibited activity (including but not limited to money-laundering or financing of terrorist activities)
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
name: Beyond Pricing
provenance_date: '2026-11-09'
provider_name: Beyond Pricing
provider_slug: beyond-pricing
slug: beyond-pricing-eligibility
source_date: '2026-11-09'
source_filename: beyond-pricing-eligibility.yml
source_heading: Eligibility
source_page: https://beyondpricing.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beyond Pricing\naid: beyond-pricing\nurl: https://beyondpricing.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Beyond makes no representations that the Services are appropriate for use in other jurisdictions; users\n    must comply with export laws and not access Services in U.S. embargoed countries or regions.\nentity_types:\n- type: business\n  text: If using the Services on behalf of an organization, User agrees to this Agreement on behalf of that organization\n    and attests that User has the authority to bind that organization to this Agreement.\n\
  restricted_uses:\n- summary: Illegal or prohibited activity\n  text: not use the Services, and ensure that Sub-Users do not use the Services, to engage in illegal or prohibited\n    activity (including but not limited to money-laundering or financing of terrorist activities)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: must be at least 18 years of age, or the age of legal majority in User's jurisdiction if different than\n    18.\n"
source_yaml_url: https://artifacts.apis.io/beyond-pricing/eligibility/beyond-pricing-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beyond Pricing's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Short-Term Rental
- Vacation Rentals
- Revenue Management
- Dynamic Pricing
- Hospitality
- Property Management
- Travel
- Pricing
- JSON:API
---
