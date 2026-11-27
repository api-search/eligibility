---
api_specs:
- filename: stubhub-addressess-api-openapi.yml
  format: yaml
  label: StubHub Addressess API
  slug: stubhub-addressess-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-addressess-api-openapi.yml
- filename: stubhub-categories-api-openapi.yml
  format: yaml
  label: StubHub Categories API
  slug: stubhub-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-categories-api-openapi.yml
- filename: stubhub-e-tickets-api-openapi.yml
  format: yaml
  label: StubHub E-Tickets API
  slug: stubhub-e-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-e-tickets-api-openapi.yml
- filename: stubhub-events-api-openapi.yml
  format: yaml
  label: StubHub Events API
  slug: stubhub-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-events-api-openapi.yml
- filename: stubhub-listingconstraints-api-openapi.yml
  format: yaml
  label: StubHub ListingConstraints API
  slug: stubhub-listingconstraints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-listingconstraints-api-openapi.yml
- filename: stubhub-payments-api-openapi.yml
  format: yaml
  label: StubHub Payments API
  slug: stubhub-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-payments-api-openapi.yml
- filename: stubhub-sales-api-openapi.yml
  format: yaml
  label: StubHub Sales API
  slug: stubhub-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-sales-api-openapi.yml
- filename: stubhub-sellerevents-api-openapi.yml
  format: yaml
  label: StubHub SellerEvents API
  slug: stubhub-sellerevents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-sellerevents-api-openapi.yml
- filename: stubhub-sellerlistings-api-openapi.yml
  format: yaml
  label: StubHub SellerListings API
  slug: stubhub-sellerlistings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-sellerlistings-api-openapi.yml
- filename: stubhub-shipments-api-openapi.yml
  format: yaml
  label: StubHub Shipments API
  slug: stubhub-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-shipments-api-openapi.yml
- filename: stubhub-ticketholders-api-openapi.yml
  format: yaml
  label: StubHub TicketHolders API
  slug: stubhub-ticketholders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-ticketholders-api-openapi.yml
- filename: stubhub-user-api-openapi.yml
  format: yaml
  label: StubHub User API
  slug: stubhub-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-user-api-openapi.yml
- filename: stubhub-venues-api-openapi.yml
  format: yaml
  label: StubHub Venues API
  slug: stubhub-venues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-venues-api-openapi.yml
- filename: stubhub-webhooks-api-openapi.yml
  format: yaml
  label: StubHub Webhooks API
  slug: stubhub-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-webhooks-api-openapi.yml
- filename: stubhub-payment-methods-api-openapi.yml
  format: yaml
  label: StubHub Payment Methods API
  slug: stubhub-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stubhub/openapi/stubhub-payment-methods-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and must be able to enter into legally binding contracts.
    type: individual
  - text: If you are registering with us for a business entity, you represent that you have the authority to legally bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and must be able to enter into legally binding contracts.
    value: '18'
  restricted_uses:
  - summary: Sanctioned territories and persons
    text: you represent and warrant that you are not located in a Sanctioned Territory, and that you are not a Sanctioned Person.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: When opening an Account you must provide complete and accurate information including but not limited to your full name, address, phone number, email address and provide us with a valid credit card, debit card or PayPal account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: StubHub
provenance_date: '2026-11-10'
provider_name: StubHub
provider_slug: stubhub
slug: stubhub-eligibility
source_date: '2026-11-10'
source_filename: stubhub-eligibility.yml
source_heading: Eligibility
source_page: https://www.stubhub.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StubHub\naid: stubhub\nurl: https://www.stubhub.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and must be able to enter into legally binding contracts.\n- type: business\n  text: If you are registering with us for a business entity, you represent that you have the authority to legally\n    bind that entity.\nrestricted_uses:\n- summary: Sanctioned territories and persons\n  text: you represent and warrant that you are not located in a Sanctioned Territory, and that you\
  \ are not a Sanctioned\n    Person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: When opening an Account you must provide complete and accurate information including but not limited to\n    your full name, address, phone number, email address and provide us with a valid credit card, debit card or\n    PayPal account\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and must be able to enter into legally binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/stubhub/eligibility/stubhub-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from StubHub's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Ticketing
- Event
- Live Events
- Secondary Market
- E-Commerce
- Sports
- Concerts
---
