---
api_specs:
- filename: convoy-delivery-attempts-api-openapi.yml
  format: yaml
  label: Convoy Delivery Attempts API
  slug: convoy-delivery-attempts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-delivery-attempts-api-openapi.yml
- filename: convoy-endpoints-api-openapi.yml
  format: yaml
  label: Convoy Endpoints API
  slug: convoy-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-endpoints-api-openapi.yml
- filename: convoy-event-deliveries-api-openapi.yml
  format: yaml
  label: Convoy Event Deliveries API
  slug: convoy-event-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-event-deliveries-api-openapi.yml
- filename: convoy-events-api-openapi.yml
  format: yaml
  label: Convoy Events API
  slug: convoy-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-events-api-openapi.yml
- filename: convoy-filters-api-openapi.yml
  format: yaml
  label: Convoy Filters API
  slug: convoy-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-filters-api-openapi.yml
- filename: convoy-meta-events-api-openapi.yml
  format: yaml
  label: Convoy Meta Events API
  slug: convoy-meta-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-meta-events-api-openapi.yml
- filename: convoy-onboard-api-openapi.yml
  format: yaml
  label: Convoy Onboard API
  slug: convoy-onboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-onboard-api-openapi.yml
- filename: convoy-portal-links-api-openapi.yml
  format: yaml
  label: Convoy Portal Links API
  slug: convoy-portal-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-portal-links-api-openapi.yml
- filename: convoy-sources-api-openapi.yml
  format: yaml
  label: Convoy Sources API
  slug: convoy-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-sources-api-openapi.yml
- filename: convoy-subscriptions-api-openapi.yml
  format: yaml
  label: Convoy Subscriptions API
  slug: convoy-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-subscriptions-api-openapi.yml
- filename: convoy-event-types-api-openapi.yml
  format: yaml
  label: Convoy Event Types API
  slug: convoy-event-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convoy/openapi/convoy-event-types-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Children under 18 years of age, may use the Services only with the involvement of a parent or guardian.
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
name: Convoy
provenance_date: '2026-11-09'
provider_name: Convoy
provider_slug: convoy
slug: convoy-eligibility
source_date: '2026-11-09'
source_filename: convoy-eligibility.yml
source_heading: Eligibility
source_page: https://www.getconvoy.io/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Convoy\naid: convoy\nurl: https://www.getconvoy.io/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Children under 18 years of age, may use the Services only with the involvement of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/convoy/eligibility/convoy-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Convoy's own page on 2026-11-09.
synthetic: false
tags:
- Webhook
- Webhook Gateway
- Event Delivery
- Eventing
- Messaging
- Integration
- API Infrastructure
---
