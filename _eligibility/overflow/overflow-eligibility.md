---
api_specs:
- filename: overflow-campaigns-api-openapi.yml
  format: yaml
  label: Overflow Campaigns API
  slug: overflow-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-campaigns-api-openapi.yml
- filename: overflow-chargebacks-api-openapi.yml
  format: yaml
  label: Overflow Chargebacks API
  slug: overflow-chargebacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-chargebacks-api-openapi.yml
- filename: overflow-contributions-api-openapi.yml
  format: yaml
  label: Overflow Contributions API
  slug: overflow-contributions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-contributions-api-openapi.yml
- filename: overflow-deposits-api-openapi.yml
  format: yaml
  label: Overflow Deposits API
  slug: overflow-deposits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-deposits-api-openapi.yml
- filename: overflow-donors-api-openapi.yml
  format: yaml
  label: Overflow Donors API
  slug: overflow-donors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-donors-api-openapi.yml
- filename: overflow-locations-api-openapi.yml
  format: yaml
  label: Overflow Locations API
  slug: overflow-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-locations-api-openapi.yml
- filename: overflow-payment-methods-api-openapi.yml
  format: yaml
  label: Overflow Payment Methods API
  slug: overflow-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-payment-methods-api-openapi.yml
- filename: overflow-payments-api-openapi.yml
  format: yaml
  label: Overflow Payments API
  slug: overflow-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-payments-api-openapi.yml
- filename: overflow-refunds-api-openapi.yml
  format: yaml
  label: Overflow Refunds API
  slug: overflow-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-refunds-api-openapi.yml
- filename: overflow-status-api-openapi.yml
  format: yaml
  label: Overflow Status API
  slug: overflow-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-status-api-openapi.yml
- filename: overflow-subscriptions-api-openapi.yml
  format: yaml
  label: Overflow Subscriptions API
  slug: overflow-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-subscriptions-api-openapi.yml
- filename: overflow-tap-api-openapi.yml
  format: yaml
  label: Overflow Tap API
  slug: overflow-tap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-tap-api-openapi.yml
- filename: overflow-webhooks-api-openapi.yml
  format: yaml
  label: Overflow Webhooks API
  slug: overflow-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overflow/openapi/overflow-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Platform, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Embargoed countries/sanctions
    text: not to use the Platform in or for the benefit of a country, organization, entity, or person embargoed or blocked by any government, including those on sanctions lists identified by the United States Office of Foreign Asset Control (OFAC)
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Overflow is under no obligation to accept any individual as a Registered User, and may accept or reject any registration in its sole and complete discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Overflow
provenance_date: '2026-11-10'
provider_name: Overflow
provider_slug: overflow
slug: overflow-eligibility
source_date: '2026-11-10'
source_filename: overflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.overflow.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Overflow\naid: overflow\nurl: https://www.overflow.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Embargoed countries/sanctions\n  text: not to use the Platform in or for the benefit of a country, organization, entity, or person embargoed or\n    blocked by any government, including those on sanctions lists identified by the United States Office of Foreign\n    Asset Control (OFAC)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Overflow is under no obligation to accept any individual as a\
  \ Registered User, and may accept or reject\n    any registration in its sole and complete discretion.\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Platform, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/overflow/eligibility/overflow-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Overflow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Donations
- Fundraising
- Non-Profit
- Giving
- Recurring Payments
- Webhook
- Cryptocurrency
---
