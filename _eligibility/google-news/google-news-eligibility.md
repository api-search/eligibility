---
api_specs:
- filename: google-news-headlines-api-openapi.yml
  format: yaml
  label: Google News RSS Headlines API
  slug: google-news-headlines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-news/openapi/google-news-headlines-api-openapi.yml
- filename: google-news-search-api-openapi.yml
  format: yaml
  label: Google News RSS Search API
  slug: google-news-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-news/openapi/google-news-search-api-openapi.yml
- filename: google-news-topics-api-openapi.yml
  format: yaml
  label: Google News RSS Topics API
  slug: google-news-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-news/openapi/google-news-topics-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you’re a business user or organization
    type: business
  minimum_age:
    text: If you’re under the age required to manage your own Google Account , you must have your parent or legal guardian’s permission to use a Google Account.
    value: null
  restricted_uses:
  - summary: No reliance for professional advice
    text: UNLESS EXPLICITLY PERMITTED BY SERVICE-SPECIFIC ADDITIONAL TERMS , DON’T RELY ON THE SERVICES FOR MEDICAL, LEGAL, FINANCIAL, OR OTHER PROFESSIONAL ADVICE.
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
name: Google News RSS
provenance_date: '2026-11-09'
provider_name: Google News RSS
provider_slug: google-news
slug: google-news-eligibility
source_date: '2026-11-09'
source_filename: google-news-eligibility.yml
source_heading: Eligibility
source_page: https://policies.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google News RSS\naid: google-news\nurl: https://policies.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re a business user or organization\nrestricted_uses:\n- summary: No reliance for professional advice\n  text: UNLESS EXPLICITLY PERMITTED BY SERVICE-SPECIFIC ADDITIONAL TERMS , DON’T RELY ON THE SERVICES FOR MEDICAL,\n    LEGAL, FINANCIAL, OR OTHER PROFESSIONAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you’re under the\
  \ age required to manage your own Google Account , you must have your parent or legal\n    guardian’s permission to use a Google Account.\n"
source_yaml_url: https://artifacts.apis.io/google-news/eligibility/google-news-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Google News RSS's own page on 2026-11-09.
synthetic: false
tags:
- Aggregation
- Google News
- Headlines
- Media
- News
- RSS
---
