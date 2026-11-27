---
api_specs:
- filename: finedata-ai-api-keys-api-openapi.yml
  format: yaml
  label: finedata-ai API Keys API
  slug: finedata-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-api-keys-api-openapi.yml
- filename: finedata-ai-async-scraping-api-openapi.yml
  format: yaml
  label: finedata-ai Async Scraping API
  slug: finedata-ai-async-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-async-scraping-api-openapi.yml
- filename: finedata-ai-google-serp-api-openapi.yml
  format: yaml
  label: finedata-ai Google SERP API
  slug: finedata-ai-google-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-google-serp-api-openapi.yml
- filename: finedata-ai-oauth-api-openapi.yml
  format: yaml
  label: finedata-ai OAuth API
  slug: finedata-ai-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-oauth-api-openapi.yml
- filename: finedata-ai-plans-api-openapi.yml
  format: yaml
  label: finedata-ai Plans API
  slug: finedata-ai-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-plans-api-openapi.yml
- filename: finedata-ai-proxy-profiles-byop-api-openapi.yml
  format: yaml
  label: finedata-ai Proxy Profiles (BYOP) API
  slug: finedata-ai-proxy-profiles-byop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-proxy-profiles-byop-api-openapi.yml
- filename: finedata-ai-user-api-openapi.yml
  format: yaml
  label: finedata-ai User API
  slug: finedata-ai-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-user-api-openapi.yml
- filename: finedata-ai-user-statistics-api-openapi.yml
  format: yaml
  label: finedata-ai User Statistics API
  slug: finedata-ai-user-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-user-statistics-api-openapi.yml
- filename: finedata-ai-web-scraping-api-openapi.yml
  format: yaml
  label: finedata-ai Web Scraping API
  slug: finedata-ai-web-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-web-scraping-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: Be at least 18 years of age (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Personal data scraping without legal basis
    text: You may not use the Service to scrape personal data without proper legal basis
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
name: finedata-ai
provenance_date: '2026-11-09'
provider_name: finedata-ai
provider_slug: finedata-ai
slug: finedata-ai-eligibility
source_date: '2026-11-09'
source_filename: finedata-ai-eligibility.yml
source_heading: Eligibility
source_page: https://finedata.ai/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: finedata-ai\naid: finedata-ai\nurl: https://finedata.ai/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Personal data scraping without legal basis\n  text: You may not use the Service to scrape personal data without proper legal basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: Be at least 18 years of age (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/finedata-ai/eligibility/finedata-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from finedata-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Web Scraping
- Data Extraction
- MCP
- LLM
---
