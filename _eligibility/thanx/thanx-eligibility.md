---
api_specs:
- filename: thanx-account-api-openapi.yml
  format: yaml
  label: Thanx Account API
  slug: thanx-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-account-api-openapi.yml
- filename: thanx-auth-api-openapi.yml
  format: yaml
  label: Thanx Auth API
  slug: thanx-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-auth-api-openapi.yml
- filename: thanx-baskets-api-openapi.yml
  format: yaml
  label: Thanx Baskets API
  slug: thanx-baskets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-baskets-api-openapi.yml
- filename: thanx-campaigns-api-openapi.yml
  format: yaml
  label: Thanx Campaigns API
  slug: thanx-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-campaigns-api-openapi.yml
- filename: thanx-cards-api-openapi.yml
  format: yaml
  label: Thanx Cards API
  slug: thanx-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-cards-api-openapi.yml
- filename: thanx-gift-cards-api-openapi.yml
  format: yaml
  label: Thanx Gift Cards API
  slug: thanx-gift-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-gift-cards-api-openapi.yml
- filename: thanx-issuance-jobs-api-openapi.yml
  format: yaml
  label: Thanx Issuance Jobs API
  slug: thanx-issuance-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-issuance-jobs-api-openapi.yml
- filename: thanx-locations-api-openapi.yml
  format: yaml
  label: Thanx Locations API
  slug: thanx-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-locations-api-openapi.yml
- filename: thanx-metadata-api-openapi.yml
  format: yaml
  label: Thanx Metadata API
  slug: thanx-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-metadata-api-openapi.yml
- filename: thanx-points-api-openapi.yml
  format: yaml
  label: Thanx Points API
  slug: thanx-points-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-points-api-openapi.yml
- filename: thanx-purchases-api-openapi.yml
  format: yaml
  label: Thanx Purchases API
  slug: thanx-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-purchases-api-openapi.yml
- filename: thanx-rewards-api-openapi.yml
  format: yaml
  label: Thanx Rewards API
  slug: thanx-rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-rewards-api-openapi.yml
- filename: thanx-subscribers-api-openapi.yml
  format: yaml
  label: Thanx Subscribers API
  slug: thanx-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-subscribers-api-openapi.yml
- filename: thanx-users-api-openapi.yml
  format: yaml
  label: Thanx Users API
  slug: thanx-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanx/openapi/thanx-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be an individual person at least 18 years of age;
    type: individual
  minimum_age:
    text: Be an individual person at least 18 years of age;
    value: '18'
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
name: Thanx
provenance_date: '2026-11-10'
provider_name: Thanx
provider_slug: thanx
slug: thanx-eligibility
source_date: '2026-11-10'
source_filename: thanx-eligibility.yml
source_heading: Eligibility
source_page: https://dashboard.thanx.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thanx\naid: thanx\nurl: https://dashboard.thanx.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be an individual person at least 18 years of age;\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be an individual person at least 18 years of age;\n"
source_yaml_url: https://artifacts.apis.io/thanx/eligibility/thanx-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Thanx's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Loyalty
- Guest Engagement
- Marketing
- CRM
- Online Ordering
- Webhook
- Points
- Rewards
- Campaigns
- A2A
- Loyalty & Incentives
---
