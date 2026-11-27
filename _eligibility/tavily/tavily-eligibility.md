---
api_specs:
- filename: tavily-crawl-api-openapi.yml
  format: yaml
  label: Tavily Crawl API
  slug: tavily-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-crawl-api-openapi.yml
- filename: tavily-extract-api-openapi.yml
  format: yaml
  label: Tavily Extract API
  slug: tavily-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-extract-api-openapi.yml
- filename: tavily-map-api-openapi.yml
  format: yaml
  label: Tavily Map API
  slug: tavily-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-map-api-openapi.yml
- filename: tavily-research-api-openapi.yml
  format: yaml
  label: Tavily Research API
  slug: tavily-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-research-api-openapi.yml
- filename: tavily-search-api-openapi.yml
  format: yaml
  label: Tavily Search API
  slug: tavily-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: as an individual, company, or other legal entity, as identified by the information you provided when creating your Account
    type: individual
  - text: If you are accepting this Agreement on behalf of a company, organization, or other legal entity, you are authorized to accept
    type: business
  minimum_age:
    text: You are at least eighteen (18) years of age or have reached the age of majority in your jurisdiction, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Safety-critical, medical, legal, financial decisions
    text: you specifically agree that you will not use the AI Functionality or Outputs in connection with safety-critical systems, medical diagnosis or treatment decisions, legal proceedings or legal advice, financial investment decisions, regulatory compliance determinations
  - summary: Deepfakes and deceptive synthetic media
    text: You may not use the AI Functionality to create deepfakes, synthetic media, or other artificially generated content intended to deceive, mislead, or manipulate others
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
name: Tavily
provenance_date: '2026-11-10'
provider_name: Tavily
provider_slug: tavily
slug: tavily-eligibility
source_date: '2026-11-10'
source_filename: tavily-eligibility.yml
source_heading: Eligibility
source_page: https://www.tavily.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tavily\naid: tavily\nurl: https://www.tavily.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: as an individual, company, or other legal entity, as identified by the information you provided when creating\n    your Account\n- type: business\n  text: If you are accepting this Agreement on behalf of a company, organization, or other legal entity, you are\n    authorized to accept\nrestricted_uses:\n- summary: Safety-critical, medical, legal, financial decisions\n  text: you specifically agree that you will\
  \ not use the AI Functionality or Outputs in connection with safety-critical\n    systems, medical diagnosis or treatment decisions, legal proceedings or legal advice, financial investment decisions,\n    regulatory compliance determinations\n- summary: Deepfakes and deceptive synthetic media\n  text: You may not use the AI Functionality to create deepfakes, synthetic media, or other artificially generated\n    content intended to deceive, mislead, or manipulate others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least eighteen (18) years of age or have reached the age of majority in your jurisdiction, whichever\n    is greater\n"
source_yaml_url: https://artifacts.apis.io/tavily/eligibility/tavily-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Tavily's own page on 2026-11-10.
synthetic: false
tags:
- Search
- Web Search
- AI Agents
- LLM
- Extract
- Crawl
- Sitemap
- Research
- REST
- LangChain
- LlamaIndex
- Real-Time
- A2A
---
