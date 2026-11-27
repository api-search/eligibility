---
api_specs:
- filename: citedtravel-com-billing-api-openapi.yml
  format: yaml
  label: CitedTravel Billing API
  slug: citedtravel-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-billing-api-openapi.yml
- filename: citedtravel-com-entry-api-openapi.yml
  format: yaml
  label: CitedTravel Entry API
  slug: citedtravel-com-entry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-entry-api-openapi.yml
- filename: citedtravel-com-facts-api-openapi.yml
  format: yaml
  label: CitedTravel Facts API
  slug: citedtravel-com-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-facts-api-openapi.yml
- filename: citedtravel-com-meta-api-openapi.yml
  format: yaml
  label: CitedTravel Meta API
  slug: citedtravel-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-meta-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Builder and Pro are available in the countries where Stripe offers them at checkout, except where US sanctions law requires us to block paid services
  entity_types:
  - text: If you use the Service for a company or other organisation, you confirm that you may accept these Terms for it, and "you" includes that organisation.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live if that is higher, to accept these Terms, create an API key, subscribe or pay for a request.
    value: '18'
  restricted_uses:
  - summary: US sanctions restrictions on paid services
    text: We do not offer paid services (subscriptions, pay-per-call with x402 and paid MCP tools) in countries or regions under comprehensive US sanctions
  - summary: Unlawful x402 use
    text: Do not use x402 where it is not lawful for you to do so.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A free API key requires a valid email address and acceptance of these Terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CitedTravel
provenance_date: '2026-11-09'
provider_name: CitedTravel
provider_slug: citedtravel-com
slug: citedtravel-com-eligibility
source_date: '2026-11-09'
source_filename: citedtravel-com-eligibility.yml
source_heading: Eligibility
source_page: https://citedtravel.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CitedTravel\naid: citedtravel-com\nurl: https://citedtravel.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Builder and Pro are available in the countries where Stripe offers them at checkout, except where US sanctions\n    law requires us to block paid services\nentity_types:\n- type: business\n  text: If you use the Service for a company or other organisation, you confirm that you may accept these Terms\n    for it, and \"you\" includes that organisation.\nrestricted_uses:\n- summary: US sanctions restrictions on paid services\n  text: We do not offer paid services (subscriptions,\
  \ pay-per-call with x402 and paid MCP tools) in countries or\n    regions under comprehensive US sanctions\n- summary: Unlawful x402 use\n  text: Do not use x402 where it is not lawful for you to do so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A free API key requires a valid email address and acceptance of these Terms.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher, to accept these\n    Terms, create an API key, subscribe or pay for a request.\n"
source_yaml_url: https://artifacts.apis.io/citedtravel-com/eligibility/citedtravel-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from CitedTravel's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Data
- TravelFacts
- Open Data
---
