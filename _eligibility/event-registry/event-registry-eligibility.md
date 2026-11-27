---
api_specs:
- filename: event-registry-articles-api-openapi.yml
  format: yaml
  label: Event Registry Articles API
  slug: event-registry-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-articles-api-openapi.yml
- filename: event-registry-events-api-openapi.yml
  format: yaml
  label: Event Registry Events API
  slug: event-registry-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-events-api-openapi.yml
- filename: event-registry-suggest-api-openapi.yml
  format: yaml
  label: Event Registry Suggest API
  slug: event-registry-suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-suggest-api-openapi.yml
- filename: event-registry-topic-pages-api-openapi.yml
  format: yaml
  label: Event Registry Topic Pages API
  slug: event-registry-topic-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-topic-pages-api-openapi.yml
- filename: event-registry-usage-api-openapi.yml
  format: yaml
  label: Event Registry Usage API
  slug: event-registry-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/event-registry/openapi/event-registry-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must register with a company or academic email address.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Free access limited to evaluation
    text: Free access is intended solely for evaluation and testing. It may not be used for any project, research, or application that produces commercial or institutional value, even indirectly.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To register, you must use a valid company or academic email address. We do not support signups with personal or disposable email providers.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Event Registry
provenance_date: '2026-11-09'
provider_name: Event Registry
provider_slug: event-registry
slug: event-registry-eligibility
source_date: '2026-11-09'
source_filename: event-registry-eligibility.yml
source_heading: Eligibility
source_page: https://newsapi.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Event Registry\naid: event-registry\nurl: https://newsapi.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must register with a company or academic email address.\nrestricted_uses:\n- summary: Free access limited to evaluation\n  text: Free access is intended solely for evaluation and testing. It may not be used for any project, research,\n    or application that produces commercial or institutional value, even indirectly.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To register, you must use\
  \ a valid company or academic email address. We do not support signups with personal\n    or disposable email providers.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/event-registry/eligibility/event-registry-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Event Registry's own page on 2026-11-09.
synthetic: false
tags:
- News
- Media Monitoring
- News Intelligence
- Event Detection
- Named Entity Recognition
- Sentiment Analysis
- Media Analytics
- News API
---
