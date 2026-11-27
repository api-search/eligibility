---
api_specs:
- filename: crawl4ai-crawl-api-openapi.yml
  format: yaml
  label: Crawl4AI Crawl API
  slug: crawl4ai-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawl4ai/openapi/crawl4ai-crawl-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One person or organization per account unless we agree otherwise.
    type: individual
  minimum_age:
    text: The Services are not intended for anyone under 18, and we do not knowingly collect their data.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive data collection
    text: Collect personal data for unlawful, deceptive, or abusive purposes, or in breach of data-protection law or a person's rights.
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
name: Crawl4AI
provenance_date: '2026-11-09'
provider_name: Crawl4AI
provider_slug: crawl4ai
slug: crawl4ai-eligibility
source_date: '2026-11-09'
source_filename: crawl4ai-eligibility.yml
source_heading: Eligibility
source_page: https://gate.crawl4ai.com/legal/#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crawl4AI\naid: crawl4ai\nurl: https://gate.crawl4ai.com/legal/#terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One person or organization per account unless we agree otherwise.\nrestricted_uses:\n- summary: Unlawful or abusive data collection\n  text: Collect personal data for unlawful, deceptive, or abusive purposes, or in breach of data-protection law\n    or a person's rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended\
  \ for anyone under 18, and we do not knowingly collect their data.\n"
source_yaml_url: https://artifacts.apis.io/crawl4ai/eligibility/crawl4ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Crawl4AI's own page on 2026-11-09.
synthetic: false
tags:
- AI Automation
- Web Crawling
- Web Scraping
- Data Extraction
- Search
- LLM Tooling
- Agents
- MCP
- Open Source
---
