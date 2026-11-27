---
api_specs:
- filename: sheeva-authentication-api-openapi.yml
  format: yaml
  label: Sheeva Authentication API
  slug: sheeva-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-authentication-api-openapi.yml
- filename: sheeva-credit-cards-api-openapi.yml
  format: yaml
  label: Sheeva Credit Cards API
  slug: sheeva-credit-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-credit-cards-api-openapi.yml
- filename: sheeva-driver-alerts-api-openapi.yml
  format: yaml
  label: Sheeva Driver Alerts API
  slug: sheeva-driver-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-driver-alerts-api-openapi.yml
- filename: sheeva-driver-api-openapi.yml
  format: yaml
  label: Sheeva Driver API
  slug: sheeva-driver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-driver-api-openapi.yml
- filename: sheeva-feedback-api-openapi.yml
  format: yaml
  label: Sheeva Feedback API
  slug: sheeva-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-feedback-api-openapi.yml
- filename: sheeva-loyalty-api-openapi.yml
  format: yaml
  label: Sheeva Loyalty API
  slug: sheeva-loyalty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-loyalty-api-openapi.yml
- filename: sheeva-parking-api-openapi.yml
  format: yaml
  label: Sheeva Parking API
  slug: sheeva-parking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-parking-api-openapi.yml
- filename: sheeva-payments-api-openapi.yml
  format: yaml
  label: Sheeva Payments API
  slug: sheeva-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-payments-api-openapi.yml
- filename: sheeva-service-hubs-points-of-interest-api-openapi.yml
  format: yaml
  label: Sheeva Service Hubs (Points Of Interest) API
  slug: sheeva-service-hubs-points-of-interest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-service-hubs-points-of-interest-api-openapi.yml
- filename: sheeva-session-api-openapi.yml
  format: yaml
  label: Sheeva Session API
  slug: sheeva-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-session-api-openapi.yml
- filename: sheeva-transactions-api-openapi.yml
  format: yaml
  label: Sheeva Transactions API
  slug: sheeva-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-transactions-api-openapi.yml
- filename: sheeva-upi-api-openapi.yml
  format: yaml
  label: Sheeva UPI API
  slug: sheeva-upi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-upi-api-openapi.yml
- filename: sheeva-vehicle-api-openapi.yml
  format: yaml
  label: Sheeva Vehicle API
  slug: sheeva-vehicle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-vehicle-api-openapi.yml
- filename: sheeva-vehicle-events-api-openapi.yml
  format: yaml
  label: Sheeva Vehicle Events API
  slug: sheeva-vehicle-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-vehicle-events-api-openapi.yml
- filename: sheeva-webhooks-api-openapi.yml
  format: yaml
  label: Sheeva Webhooks API
  slug: sheeva-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sheeva/openapi/sheeva-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We provide the Platform solely for your personal use, except as otherwise expressly agreed to by us in writing, at our sole discretion.
    type: individual
  - text: YOU FURTHER REPRESENT AND AFFIRM THAT YOU HAVE THE AUTHORITY AND DO HEREBY LEGALLY BIND YOURSELF OR THE BUSINESS ENTITY
    type: business
  minimum_age:
    text: You are at least 16 years of age and you are authorized to provide information to Sheeva.AI through the Platform, install the Platform, and open a Sheeva.AI Account;
    value: '16'
  restricted_uses:
  - summary: Commercial activity without consent
    text: You will not Use the Platform in regard to any commercial activities, advertising or sales without the prior written consent of Sheeva.AI, which may be unreasonably withheld;
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
name: Sheeva
provenance_date: '2026-11-10'
provider_name: Sheeva
provider_slug: sheeva
slug: sheeva-eligibility
source_date: '2026-11-10'
source_filename: sheeva-eligibility.yml
source_heading: Eligibility
source_page: https://sheeva.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sheeva\naid: sheeva\nurl: https://sheeva.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We provide the Platform solely for your personal use, except as otherwise expressly agreed to by us in writing,\n    at our sole discretion.\n- type: business\n  text: YOU FURTHER REPRESENT AND AFFIRM THAT YOU HAVE THE AUTHORITY AND DO HEREBY LEGALLY BIND YOURSELF OR THE\n    BUSINESS ENTITY\nrestricted_uses:\n- summary: Commercial activity without consent\n  text: You will not Use the Platform in regard\
  \ to any commercial activities, advertising or sales without the prior\n    written consent of Sheeva.AI, which may be unreasonably withheld;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You are at least 16 years of age and you are authorized to provide information to Sheeva.AI through the\n    Platform, install the Platform, and open a Sheeva.AI Account;\n"
source_yaml_url: https://artifacts.apis.io/sheeva/eligibility/sheeva-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sheeva's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Connected Vehicles
- Automotive
- Payments
- Fintech
- In-Vehicle Payments
- EV Charging
- Parking
- Location Intelligence
- Mobility
---
