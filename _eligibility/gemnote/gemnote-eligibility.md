---
api_specs:
- filename: gemnote-gifts-api-openapi.yml
  format: yaml
  label: Gemnote Gifts API
  slug: gemnote-gifts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gemnote/openapi/gemnote-gifts-api-openapi.yml
- filename: gemnote-greeting-cards-api-openapi.yml
  format: yaml
  label: Gemnote Greeting Cards API
  slug: gemnote-greeting-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gemnote/openapi/gemnote-greeting-cards-api-openapi.yml
- filename: gemnote-shipments-api-openapi.yml
  format: yaml
  label: Gemnote Shipments API
  slug: gemnote-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gemnote/openapi/gemnote-shipments-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are of legal age in your jurisdiction or have consent from a legal guardian.
    type: individual
  - text: Brand Partner is the merchant of record for all customer transactions.
    type: business
  minimum_age:
    text: You represent that you are of legal age in your jurisdiction or have consent from a legal guardian.
    value: legal age in jurisdiction or with guardian consent
  restricted_uses:
  - summary: Scraping or misuse of data
    text: Scrape, harvest, or misuse data
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
name: Gemnote
provenance_date: '2026-11-09'
provider_name: Gemnote
provider_slug: gemnote
slug: gemnote-eligibility
source_date: '2026-11-09'
source_filename: gemnote-eligibility.yml
source_heading: Eligibility
source_page: https://www.gemnote.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gemnote\naid: gemnote\nurl: https://www.gemnote.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are of legal age in your jurisdiction or have consent from a legal guardian.\n- type: business\n  text: Brand Partner is the merchant of record for all customer transactions.\nrestricted_uses:\n- summary: Scraping or misuse of data\n  text: Scrape, harvest, or misuse data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age in jurisdiction or\
  \ with guardian consent\n  text: You represent that you are of legal age in your jurisdiction or have consent from a legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/gemnote/eligibility/gemnote-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gemnote's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Corporate Gifting
- Swag Management
- Branded Merchandise
- Fulfillment
- E-Commerce
- Shipping
- Y Combinator
---
