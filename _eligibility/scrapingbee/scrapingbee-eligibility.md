---
api_specs:
- filename: scrapingbee-google-search-api-api-openapi.yml
  format: yaml
  label: ScrapingBee Google Search API
  slug: scrapingbee-google-search-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingbee/openapi/scrapingbee-google-search-api-api-openapi.yml
- filename: scrapingbee-html-api-api-openapi.yml
  format: yaml
  label: ScrapingBee HTML API
  slug: scrapingbee-html-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingbee/openapi/scrapingbee-html-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any natural person aged at least 18 years old with full and complete legal capacity acting in the scope of their professional activity
    type: individual
  - text: or being the legal representative of a legal entity empowered to enter into legally binding commitments
    type: business
  minimum_age:
    text: any natural person aged at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Professional use only
    text: The Services are limited to an individual use by the User as part of their professional activities.
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
name: ScrapingBee
provenance_date: '2026-11-10'
provider_name: ScrapingBee
provider_slug: scrapingbee
slug: scrapingbee-eligibility
source_date: '2026-11-10'
source_filename: scrapingbee-eligibility.yml
source_heading: Eligibility
source_page: https://www.scrapingbee.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ScrapingBee\naid: scrapingbee\nurl: https://www.scrapingbee.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: any natural person aged at least 18 years old with full and complete legal capacity acting in the scope\n    of their professional activity\n- type: business\n  text: or being the legal representative of a legal entity empowered to enter into legally binding commitments\nrestricted_uses:\n- summary: Professional use only\n  text: The Services are limited to an individual use by the User as part of their\
  \ professional activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: any natural person aged at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/scrapingbee/eligibility/scrapingbee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ScrapingBee's own page on 2026-11-10.
synthetic: false
tags:
- AI Extraction
- Anti-Bot
- Data Aggregation
- Data Extraction
- Browser Automation
- JavaScript Rendering
- Proxy Rotation
- Screenshots
- Search Engines
- Web Scraping
---
