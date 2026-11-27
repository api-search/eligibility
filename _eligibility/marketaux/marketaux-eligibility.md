---
api_specs:
- filename: marketaux-entities-api-openapi.yml
  format: yaml
  label: MarketAux Entities API
  slug: marketaux-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketaux/openapi/marketaux-entities-api-openapi.yml
- filename: marketaux-news-api-openapi.yml
  format: yaml
  label: MarketAux News API
  slug: marketaux-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketaux/openapi/marketaux-news-api-openapi.yml
- filename: marketaux-sources-api-openapi.yml
  format: yaml
  label: MarketAux Sources API
  slug: marketaux-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketaux/openapi/marketaux-sources-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Industry-specific regulated data
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: GLBA use restriction
    text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: MarketAux
provenance_date: '2026-11-10'
provider_name: MarketAux
provider_slug: marketaux
slug: marketaux-eligibility
source_date: '2026-11-10'
source_filename: marketaux-eligibility.yml
source_heading: Eligibility
source_page: https://www.marketaux.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MarketAux\naid: marketaux\nurl: https://www.marketaux.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Industry-specific regulated data\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: GLBA use restriction\n\
  \  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/marketaux/eligibility/marketaux-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MarketAux's own page on 2026-11-10.
synthetic: false
tags:
- News
- Financial News
- Stock Market
- Sentiment Analysis
- Market Data
- Entity Recognition
- Public APIs
---
