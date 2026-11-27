---
api_specs:
- filename: bagsthatpay-com-dataset-api-openapi.yml
  format: yaml
  label: Bags That Pay Dataset API
  slug: bagsthatpay-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bagsthatpay-com/openapi/bagsthatpay-com-dataset-api-openapi.yml
- filename: bagsthatpay-com-enquiry-api-openapi.yml
  format: yaml
  label: Bags That Pay Enquiry API
  slug: bagsthatpay-com-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bagsthatpay-com/openapi/bagsthatpay-com-enquiry-api-openapi.yml
- filename: bagsthatpay-com-entities-api-openapi.yml
  format: yaml
  label: Bags That Pay Entities API
  slug: bagsthatpay-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bagsthatpay-com/openapi/bagsthatpay-com-entities-api-openapi.yml
- filename: bagsthatpay-com-listing-api-openapi.yml
  format: yaml
  label: Bags That Pay Listing API
  slug: bagsthatpay-com-listing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bagsthatpay-com/openapi/bagsthatpay-com-listing-api-openapi.yml
- filename: bagsthatpay-com-mcp-api-openapi.yml
  format: yaml
  label: Bags That Pay MCP API
  slug: bagsthatpay-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bagsthatpay-com/openapi/bagsthatpay-com-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Listings are accepted in the jurisdictions selected; no countries are named.
  entity_types:
  - text: The listing is a firm, adviser or provider whose work is the subject of this directory in the jurisdictions selected.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No promotion of crypto-assets to UK consumers
    text: Listings do not promote qualifying crypto-assets to UK consumers; any that does is removed.
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
name: Bags That Pay
provenance_date: '2026-11-09'
provider_name: Bags That Pay
provider_slug: bagsthatpay-com
slug: bagsthatpay-com-eligibility
source_date: '2026-11-09'
source_filename: bagsthatpay-com-eligibility.yml
source_heading: Eligibility
source_page: https://bagsthatpay.com/terms/listing/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bags That Pay\naid: bagsthatpay-com\nurl: https://bagsthatpay.com/terms/listing/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Listings are accepted in the jurisdictions selected; no countries are named.\nentity_types:\n- type: business\n  text: The listing is a firm, adviser or provider whose work is the subject of this directory in the jurisdictions\n    selected.\nrestricted_uses:\n- summary: No promotion of crypto-assets to UK consumers\n  text: Listings do not promote qualifying crypto-assets to UK consumers; any that does is removed.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bagsthatpay-com/eligibility/bagsthatpay-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Bags That Pay's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Tokenization
- Treasury-Bills
- DeFi
- Data Aggregation
---
