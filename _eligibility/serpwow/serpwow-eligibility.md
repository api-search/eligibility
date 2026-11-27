---
api_specs:
- filename: serpwow-search-api-openapi.yml
  format: yaml
  label: SerpWow Search API
  slug: serpwow-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpwow/openapi/serpwow-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: individuals who purchase a Subscription to our Service directly from us
    type: individual
  - text: individuals who are provided access to the Service by or on behalf of one of our enterprise customers
    type: other
  minimum_age:
    text: The Service may not be used by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Unlawful, prohibited, abnormal or unusual activity
    text: use the Service for any unlawful, prohibited, abnormal, or unusual activity as determined by ScraperAPI are there instances of the term “ScraperAPI” remaining on this page in its sole discretion
  - summary: Personal use only for products and services
    text: All products and services sold by or received from ScraperAPI are intended to be used for personal purposes only, and you may not sell or resell any products or services you purchase or otherwise receive from ScraperAPI.
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
name: SerpWow
provenance_date: '2026-11-10'
provider_name: SerpWow
provider_slug: serpwow
slug: serpwow-eligibility
source_date: '2026-11-10'
source_filename: serpwow-eligibility.yml
source_heading: Eligibility
source_page: https://trajectdata.com/traject-data-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SerpWow\naid: serpwow\nurl: https://trajectdata.com/traject-data-terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: individuals who purchase a Subscription to our Service directly from us\n- type: other\n  text: individuals who are provided access to the Service by or on behalf of one of our enterprise customers\nrestricted_uses:\n- summary: Unlawful, prohibited, abnormal or unusual activity\n  text: use the Service for any unlawful, prohibited, abnormal, or unusual activity as determined by ScraperAPI\n    are there\
  \ instances of the term “ScraperAPI” remaining on this page in its sole discretion\n- summary: Personal use only for products and services\n  text: All products and services sold by or received from ScraperAPI are intended to be used for personal purposes\n    only, and you may not sell or resell any products or services you purchase or otherwise receive from ScraperAPI.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service may not be used by anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/serpwow/eligibility/serpwow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SerpWow's own page on 2026-11-10.
synthetic: false
tags:
- Search
- SERP
- Web Data
- Web Scraping
- SEO
- Search Engines
- Google
- E-Commerce
- Market Intelligence
- Data Extraction
---
