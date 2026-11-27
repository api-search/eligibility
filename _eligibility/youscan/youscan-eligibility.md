---
api_specs:
- filename: youscan-data-import-api-openapi.yml
  format: yaml
  label: YouScan Data Import API
  slug: youscan-data-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-data-import-api-openapi.yml
- filename: youscan-history-api-openapi.yml
  format: yaml
  label: YouScan History API
  slug: youscan-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-history-api-openapi.yml
- filename: youscan-mentions-api-openapi.yml
  format: yaml
  label: YouScan Mentions API
  slug: youscan-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-mentions-api-openapi.yml
- filename: youscan-spaces-api-openapi.yml
  format: yaml
  label: YouScan Spaces API
  slug: youscan-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-spaces-api-openapi.yml
- filename: youscan-statistics-api-openapi.yml
  format: yaml
  label: YouScan Statistics API
  slug: youscan-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-statistics-api-openapi.yml
- filename: youscan-tags-api-openapi.yml
  format: yaml
  label: YouScan Tags API
  slug: youscan-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-tags-api-openapi.yml
- filename: youscan-topics-api-openapi.yml
  format: yaml
  label: YouScan Topics API
  slug: youscan-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-topics-api-openapi.yml
- filename: youscan-webhook-api-openapi.yml
  format: yaml
  label: YouScan Webhook API
  slug: youscan-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-webhook-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The YouScan Platform is authorized for use solely within the jurisdiction of the country where the Client is legally registered and maintains its registered address.
  entity_types:
  - text: If you are accepting these terms on behalf of an organization, you hereby represent and warrant that you possess the necessary authority to bind such organization to this Agreement.
    type: business
  - text: For purposes of this Agreement, “ Client ” shall refer to you, unless you are acting on behalf of a company
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive personal data profiling prohibited
    text: from targeting, segmenting, or profiling individuals based on sensitive personal information
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
name: YouScan
provenance_date: '2026-11-10'
provider_name: YouScan
provider_slug: youscan
slug: youscan-eligibility
source_date: '2026-11-10'
source_filename: youscan-eligibility.yml
source_heading: Eligibility
source_page: https://youscan.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: YouScan\naid: youscan\nurl: https://youscan.io/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The YouScan Platform is authorized for use solely within the jurisdiction of the country where the Client\n    is legally registered and maintains its registered address.\nentity_types:\n- type: business\n  text: If you are accepting these terms on behalf of an organization, you hereby represent and warrant that you\n    possess the necessary authority to bind such organization to this Agreement.\n- type: individual\n  text: For purposes of this Agreement,\
  \ “ Client ” shall refer to you, unless you are acting on behalf of a company\nrestricted_uses:\n- summary: Sensitive personal data profiling prohibited\n  text: from targeting, segmenting, or profiling individuals based on sensitive personal information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/youscan/eligibility/youscan-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from YouScan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media Listening
- Social Intelligence
- Consumer Insights
- Sentiment Analysis
- Media Monitoring
- Analytics
- Artificial Intelligence
---
