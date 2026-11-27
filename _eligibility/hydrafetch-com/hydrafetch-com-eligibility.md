---
api_specs:
- filename: hydrafetch-com-brand-api-openapi.yml
  format: yaml
  label: hydrafetch-com Brand API
  slug: hydrafetch-com-brand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-brand-api-openapi.yml
- filename: hydrafetch-com-crawl-batch-api-openapi.yml
  format: yaml
  label: hydrafetch-com Crawl & batch API
  slug: hydrafetch-com-crawl-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-crawl-batch-api-openapi.yml
- filename: hydrafetch-com-extract-api-openapi.yml
  format: yaml
  label: hydrafetch-com Extract API
  slug: hydrafetch-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-extract-api-openapi.yml
- filename: hydrafetch-com-feedback-api-openapi.yml
  format: yaml
  label: hydrafetch-com Feedback API
  slug: hydrafetch-com-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-feedback-api-openapi.yml
- filename: hydrafetch-com-logo-api-openapi.yml
  format: yaml
  label: hydrafetch-com Logo API
  slug: hydrafetch-com-logo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-logo-api-openapi.yml
- filename: hydrafetch-com-media-api-openapi.yml
  format: yaml
  label: hydrafetch-com Media API
  slug: hydrafetch-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-media-api-openapi.yml
- filename: hydrafetch-com-scrape-api-openapi.yml
  format: yaml
  label: hydrafetch-com Scrape API
  slug: hydrafetch-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-scrape-api-openapi.yml
- filename: hydrafetch-com-search-api-openapi.yml
  format: yaml
  label: hydrafetch-com Search API
  slug: hydrafetch-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the service on behalf of a company, you confirm you have authority to bind it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: use the service to harass, defraud, or harm others, or to distribute malware or unlawful content
  - summary: Collecting personal data without lawful basis
    text: collect personal data without a lawful basis
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
name: hydrafetch-com
provenance_date: '2026-11-09'
provider_name: hydrafetch-com
provider_slug: hydrafetch-com
slug: hydrafetch-com-eligibility
source_date: '2026-11-09'
source_filename: hydrafetch-com-eligibility.yml
source_heading: Eligibility
source_page: https://hydrafetch.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hydrafetch-com\naid: hydrafetch-com\nurl: https://hydrafetch.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the service on behalf of a company, you confirm you have authority to bind it.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: use the service to harass, defraud, or harm others, or to distribute malware or unlawful content\n- summary: Collecting personal data without lawful basis\n  text: collect personal data without a lawful basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hydrafetch-com/eligibility/hydrafetch-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from hydrafetch-com's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Data Extraction
- Automation
- Markdown
---
