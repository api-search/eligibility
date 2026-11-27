---
api_specs:
- filename: defoorreport-com-news-api-openapi.yml
  format: yaml
  label: DeFoor Report News API
  slug: defoorreport-com-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/defoorreport-com/openapi/defoorreport-com-news-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use prohibited
    text: or use it for anything unlawful.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You can sign in with your email to save stories, follow topics and connect AI apps.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DeFoor Report
provenance_date: '2026-11-09'
provider_name: DeFoor Report
provider_slug: defoorreport-com
slug: defoorreport-com-eligibility
source_date: '2026-11-09'
source_filename: defoorreport-com-eligibility.yml
source_heading: Eligibility
source_page: https://defoorreport.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeFoor Report\naid: defoorreport-com\nurl: https://defoorreport.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use prohibited\n  text: or use it for anything unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You can sign in with your email to save stories, follow topics and connect AI apps.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/defoorreport-com/eligibility/defoorreport-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from DeFoor Report's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- Artificial Intelligence
- Media
- News Aggregation
- MCP
- LLM
---
