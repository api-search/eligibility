---
api_specs:
- filename: apibara-tech-filters-api-openapi.yml
  format: yaml
  label: Apibara.tech Filters API
  slug: apibara-tech-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-filters-api-openapi.yml
- filename: apibara-tech-image-proxy-api-openapi.yml
  format: yaml
  label: Apibara.tech Image Proxy API
  slug: apibara-tech-image-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-image-proxy-api-openapi.yml
- filename: apibara-tech-locations-api-openapi.yml
  format: yaml
  label: Apibara.tech Locations API
  slug: apibara-tech-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-locations-api-openapi.yml
- filename: apibara-tech-related-vehicles-api-openapi.yml
  format: yaml
  label: Apibara.tech Related Vehicles API
  slug: apibara-tech-related-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-related-vehicles-api-openapi.yml
- filename: apibara-tech-shipping-api-openapi.yml
  format: yaml
  label: Apibara.tech Shipping API
  slug: apibara-tech-shipping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-shipping-api-openapi.yml
- filename: apibara-tech-url-tools-api-openapi.yml
  format: yaml
  label: Apibara.tech URL Tools API
  slug: apibara-tech-url-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-url-tools-api-openapi.yml
- filename: apibara-tech-usage-api-openapi.yml
  format: yaml
  label: Apibara.tech Usage API
  slug: apibara-tech-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-usage-api-openapi.yml
- filename: apibara-tech-vehicle-history-api-openapi.yml
  format: yaml
  label: Apibara.tech Vehicle History API
  slug: apibara-tech-vehicle-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-vehicle-history-api-openapi.yml
- filename: apibara-tech-vehicles-api-openapi.yml
  format: yaml
  label: Apibara.tech Vehicles API
  slug: apibara-tech-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-vehicles-api-openapi.yml
- filename: apibara-tech-change-stream-api-openapi.yml
  format: yaml
  label: Apibara.tech Change Stream API
  slug: apibara-tech-change-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-change-stream-api-openapi.yml
- filename: apibara-tech-market-api-openapi.yml
  format: yaml
  label: Apibara.tech Market API
  slug: apibara-tech-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-market-api-openapi.yml
- filename: apibara-tech-vehicle-auction-api-openapi.yml
  format: yaml
  label: Apibara.tech Vehicle Auction API
  slug: apibara-tech-vehicle-auction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibara-tech/openapi/apibara-tech-vehicle-auction-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Confirm the customer, backend and end-user countries and supported payment method before launch.
  entity_types:
  - text: You may use Apibara.tech only if you are legally able to enter into a binding agreement.
    type: individual
  - text: If you use Apibara.tech for a company, organization or client, you confirm that you are authorized to accept these Terms on their behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No official or complete records claims
    text: Do not present auction records as official or complete ownership, accident or government-title reports.
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
name: Apibara.tech
provenance_date: '2026-11-09'
provider_name: Apibara.tech
provider_slug: apibara-tech
slug: apibara-tech-eligibility
source_date: '2026-11-09'
source_filename: apibara-tech-eligibility.yml
source_heading: Eligibility
source_page: https://apibara.tech/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apibara.tech\naid: apibara-tech\nurl: https://apibara.tech/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Confirm the customer, backend and end-user countries and supported payment method before launch.\nentity_types:\n- type: individual\n  text: You may use Apibara.tech only if you are legally able to enter into a binding agreement.\n- type: business\n  text: If you use Apibara.tech for a company, organization or client, you confirm that you are authorized to accept\n    these Terms on their behalf.\nrestricted_uses:\n- summary: No official or complete records claims\n\
  \  text: Do not present auction records as official or complete ownership, accident or government-title reports.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apibara-tech/eligibility/apibara-tech-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Apibara.tech's own page on 2026-11-09.
synthetic: false
tags:
- Automotive
- vehicle-auction-data
- Copart
- IAAI
- vin-history
- Marketplace
- REST API
- Vehicle Auctions
- Salvage Auctions
- VIN Data
- Used-Car Marketplace Data
- Data Infrastructure
- Data as a Service
- REST
- JSON:API
- MCP
- Agent-Native
---
