---
api_specs:
- filename: prosperstack-customer-portal-api-openapi.yml
  format: yaml
  label: ProsperStack Customer Portal API
  slug: prosperstack-customer-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-customer-portal-api-openapi.yml
- filename: prosperstack-events-api-openapi.yml
  format: yaml
  label: ProsperStack Events API
  slug: prosperstack-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-events-api-openapi.yml
- filename: prosperstack-flow-sessions-api-openapi.yml
  format: yaml
  label: ProsperStack Flow Sessions API
  slug: prosperstack-flow-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-flow-sessions-api-openapi.yml
- filename: prosperstack-flows-api-openapi.yml
  format: yaml
  label: ProsperStack Flows API
  slug: prosperstack-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-flows-api-openapi.yml
- filename: prosperstack-offer-links-api-openapi.yml
  format: yaml
  label: ProsperStack Offer Links API
  slug: prosperstack-offer-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-offer-links-api-openapi.yml
- filename: prosperstack-offers-api-openapi.yml
  format: yaml
  label: ProsperStack Offers API
  slug: prosperstack-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-offers-api-openapi.yml
- filename: prosperstack-payments-api-openapi.yml
  format: yaml
  label: ProsperStack Payments API
  slug: prosperstack-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-payments-api-openapi.yml
- filename: prosperstack-properties-api-openapi.yml
  format: yaml
  label: ProsperStack Properties API
  slug: prosperstack-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-properties-api-openapi.yml
- filename: prosperstack-subscribers-api-openapi.yml
  format: yaml
  label: ProsperStack Subscribers API
  slug: prosperstack-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-subscribers-api-openapi.yml
- filename: prosperstack-subscriptions-api-openapi.yml
  format: yaml
  label: ProsperStack Subscriptions API
  slug: prosperstack-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-subscriptions-api-openapi.yml
- filename: prosperstack-webhooks-api-openapi.yml
  format: yaml
  label: ProsperStack Webhooks API
  slug: prosperstack-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “you” applies to both individuals and entities that access or use our Services.
    type: individual
  - text: “you” applies to both individuals and entities that access or use our Services.
    type: business
  minimum_age:
    text: Access to and use of our Services is only for those over the age of 16.
    value: '16'
  restricted_uses:
  - summary: US sanctions
    text: You expressly represent and warrant that your use of our Services and/or associated services and products is not contrary to applicable U.S. Sanctions.
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
name: ProsperStack
provenance_date: '2026-11-10'
provider_name: ProsperStack
provider_slug: prosperstack
slug: prosperstack-eligibility
source_date: '2026-11-10'
source_filename: prosperstack-eligibility.yml
source_heading: Eligibility
source_page: https://prosperstack.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ProsperStack\naid: prosperstack\nurl: https://prosperstack.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “you” applies to both individuals and entities that access or use our Services.\n- type: business\n  text: “you” applies to both individuals and entities that access or use our Services.\nrestricted_uses:\n- summary: US sanctions\n  text: You expressly represent and warrant that your use of our Services and/or associated services and products\n    is not contrary to applicable U.S. Sanctions.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Access to and use of our Services is only for those over the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/prosperstack/eligibility/prosperstack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ProsperStack's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retention
- Subscription
- Analytics
- Software-as-a-Service
---
