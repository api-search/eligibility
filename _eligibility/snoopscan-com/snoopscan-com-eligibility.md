---
api_specs:
- filename: snoopscan-com-company-api-openapi.yml
  format: yaml
  label: snoopscan-com Company API
  slug: snoopscan-com-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-company-api-openapi.yml
- filename: snoopscan-com-crawl-api-openapi.yml
  format: yaml
  label: snoopscan-com Crawl API
  slug: snoopscan-com-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-crawl-api-openapi.yml
- filename: snoopscan-com-domain-api-openapi.yml
  format: yaml
  label: snoopscan-com Domain API
  slug: snoopscan-com-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-domain-api-openapi.yml
- filename: snoopscan-com-extract-api-openapi.yml
  format: yaml
  label: snoopscan-com Extract API
  slug: snoopscan-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-extract-api-openapi.yml
- filename: snoopscan-com-fetch-api-openapi.yml
  format: yaml
  label: snoopscan-com Fetch API
  slug: snoopscan-com-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-fetch-api-openapi.yml
- filename: snoopscan-com-leads-api-openapi.yml
  format: yaml
  label: snoopscan-com Leads API
  slug: snoopscan-com-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-leads-api-openapi.yml
- filename: snoopscan-com-mentions-api-openapi.yml
  format: yaml
  label: snoopscan-com Mentions API
  slug: snoopscan-com-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-mentions-api-openapi.yml
- filename: snoopscan-com-monitor-api-openapi.yml
  format: yaml
  label: snoopscan-com Monitor API
  slug: snoopscan-com-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-monitor-api-openapi.yml
- filename: snoopscan-com-parse-api-openapi.yml
  format: yaml
  label: snoopscan-com Parse API
  slug: snoopscan-com-parse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-parse-api-openapi.yml
- filename: snoopscan-com-places-api-openapi.yml
  format: yaml
  label: snoopscan-com Places API
  slug: snoopscan-com-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-places-api-openapi.yml
- filename: snoopscan-com-platforms-api-openapi.yml
  format: yaml
  label: snoopscan-com Platforms API
  slug: snoopscan-com-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-platforms-api-openapi.yml
- filename: snoopscan-com-scrape-api-openapi.yml
  format: yaml
  label: snoopscan-com Scrape API
  slug: snoopscan-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-scrape-api-openapi.yml
- filename: snoopscan-com-serp-api-openapi.yml
  format: yaml
  label: snoopscan-com Serp API
  slug: snoopscan-com-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-serp-api-openapi.yml
- filename: snoopscan-com-social-api-openapi.yml
  format: yaml
  label: snoopscan-com Social API
  slug: snoopscan-com-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-social-api-openapi.yml
- filename: snoopscan-com-source-api-openapi.yml
  format: yaml
  label: snoopscan-com Source API
  slug: snoopscan-com-source-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-source-api-openapi.yml
- filename: snoopscan-com-templates-api-openapi.yml
  format: yaml
  label: snoopscan-com Templates API
  slug: snoopscan-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snoopscan-com/openapi/snoopscan-com-templates-api-openapi.yml
claim_count: 1
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
  - summary: Acceptable use restrictions
    text: You may not use the service to break the law, to access systems you are not permitted to access, to collect personal data in breach of the laws that apply to you, or to overload a website.
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
name: snoopscan-com
provenance_date: '2026-11-10'
provider_name: snoopscan-com
provider_slug: snoopscan-com
slug: snoopscan-com-eligibility
source_date: '2026-11-10'
source_filename: snoopscan-com-eligibility.yml
source_heading: Eligibility
source_page: https://snoopscan.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: snoopscan-com\naid: snoopscan-com\nurl: https://snoopscan.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: You may not use the service to break the law, to access systems you are not permitted to access, to collect\n    personal data in breach of the laws that apply to you, or to overload a website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/snoopscan-com/eligibility/snoopscan-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from snoopscan-com's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- AI Agents
- MCP
- Data Extraction
---
