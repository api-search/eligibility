---
api_specs:
- filename: webcrawlerapi-com-agent-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Agent API
  slug: webcrawlerapi-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-agent-api-openapi.yml
- filename: webcrawlerapi-com-feeds-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Feeds API
  slug: webcrawlerapi-com-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-feeds-api-openapi.yml
- filename: webcrawlerapi-com-jobs-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Jobs API
  slug: webcrawlerapi-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-jobs-api-openapi.yml
- filename: webcrawlerapi-com-organization-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Organization API
  slug: webcrawlerapi-com-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-organization-api-openapi.yml
- filename: webcrawlerapi-com-status-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Status API
  slug: webcrawlerapi-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-status-api-openapi.yml
- filename: webcrawlerapi-com-v2-scraping-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI V2 Scraping API
  slug: webcrawlerapi-com-v2-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-v2-scraping-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, organized under, or ordinarily resident in a restricted jurisdiction, and not on any denied-party list.
  entity_types:
  - text: If you use the Service on behalf of a company or other legal entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) and legally capable of entering into contracts.
    value: '18'
  restricted_uses:
  - summary: Unlawful or sensitive data collection
    text: use the Service to collect sensitive data in violation of law
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
name: WebCrawlerAPI
provenance_date: '2026-11-10'
provider_name: WebCrawlerAPI
provider_slug: webcrawlerapi-com
slug: webcrawlerapi-com-eligibility
source_date: '2026-11-10'
source_filename: webcrawlerapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://webcrawlerapi.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WebCrawlerAPI\naid: webcrawlerapi-com\nurl: https://webcrawlerapi.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, organized under, or ordinarily resident in a restricted jurisdiction,\n    and not on any denied-party list.\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or other legal entity, you represent that you have authority\n    to bind that entity.\nrestricted_uses:\n- summary: Unlawful or sensitive data collection\n  text: use the Service to collect sensitive data in violation of law\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) and legally capable of entering\n    into contracts.\n"
source_yaml_url: https://artifacts.apis.io/webcrawlerapi-com/eligibility/webcrawlerapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from WebCrawlerAPI's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- Web Crawling
- Data Extraction
- Markdown
- AI Agents
- LLM
- RAG
- Web Feeds
- Change Detection
- Structured Data
- MCP
- A2A
- Agent-Native
---
