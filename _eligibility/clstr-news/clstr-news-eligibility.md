---
api_specs:
- filename: clstr-news-openapi-generated.yml
  format: yaml
  label: CLSTR API
  slug: clstr-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clstr-news/openapi/_ae-authored/clstr-news-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer, you keep the protections of the mandatory consumer law of your country of residence and may bring proceedings in its courts.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful use, rights infringement or harassment
    text: (d) use the service to violate the law, infringe rights, or harass others
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
name: CLSTR
provenance_date: '2026-11-09'
provider_name: CLSTR
provider_slug: clstr-news
slug: clstr-news-eligibility
source_date: '2026-11-09'
source_filename: clstr-news-eligibility.yml
source_heading: Eligibility
source_page: https://clstr.news/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CLSTR\naid: clstr-news\nurl: https://clstr.news/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer, you keep the protections of the mandatory consumer law of your country of residence\n    and may bring proceedings in its courts.\nrestricted_uses:\n- summary: No unlawful use, rights infringement or harassment\n  text: (d) use the service to violate the law, infringe rights, or harass others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/clstr-news/eligibility/clstr-news-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CLSTR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- News API
- MCP
- AI Agents
- News Clustering
- Media Monitoring
- Summarization
---
