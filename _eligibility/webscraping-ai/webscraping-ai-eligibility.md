---
api_specs:
- filename: webscraping-ai-account-api-openapi.yml
  format: yaml
  label: WebScraping.AI Account API
  slug: webscraping-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-account-api-openapi.yml
- filename: webscraping-ai-ai-api-openapi.yml
  format: yaml
  label: WebScraping.AI AI API
  slug: webscraping-ai-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-ai-api-openapi.yml
- filename: webscraping-ai-html-api-openapi.yml
  format: yaml
  label: WebScraping.AI HTML API
  slug: webscraping-ai-html-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-html-api-openapi.yml
- filename: webscraping-ai-selected-html-api-openapi.yml
  format: yaml
  label: WebScraping.AI Selected HTML API
  slug: webscraping-ai-selected-html-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-selected-html-api-openapi.yml
- filename: webscraping-ai-text-api-openapi.yml
  format: yaml
  label: WebScraping.AI Text API
  slug: webscraping-ai-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-text-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site and Service are offered exclusively for use by businesses, not consumers.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Site and Service.
    value: '18'
  restricted_uses:
  - summary: Unauthorized account access on target sites
    text: 'You shall not use the Service to: (a) access a Target Website by logging in or authenticating into a user account'
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
name: WebScraping.AI
provenance_date: '2026-11-10'
provider_name: WebScraping.AI
provider_slug: webscraping-ai
slug: webscraping-ai-eligibility
source_date: '2026-11-10'
source_filename: webscraping-ai-eligibility.yml
source_heading: Eligibility
source_page: https://webscraping.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WebScraping.AI\naid: webscraping-ai\nurl: https://webscraping.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Site and Service are offered exclusively for use by businesses, not consumers.\nrestricted_uses:\n- summary: Unauthorized account access on target sites\n  text: 'You shall not use the Service to: (a) access a Target Website by logging in or authenticating into a user\n    account'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at\
  \ least 18 years of age to use the Site and Service.\n"
source_yaml_url: https://artifacts.apis.io/webscraping-ai/eligibility/webscraping-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from WebScraping.AI's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- Data Extraction
- Proxies
- Artificial Intelligence
- Browser Automation
- MCP
- Development
- Public APIs
- HTML
- LLM Tools
- Structured Data
- CAPTCHA
---
