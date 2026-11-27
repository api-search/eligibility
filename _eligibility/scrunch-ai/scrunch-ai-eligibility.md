---
api_specs:
- filename: scrunch-ai-agent-traffic-api-openapi.yml
  format: yaml
  label: Scrunch AI Agent Traffic API
  slug: scrunch-ai-agent-traffic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-agent-traffic-api-openapi.yml
- filename: scrunch-ai-ai-referrals-api-openapi.yml
  format: yaml
  label: Scrunch AI AI Referrals API
  slug: scrunch-ai-ai-referrals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-ai-referrals-api-openapi.yml
- filename: scrunch-ai-axp-render-api-openapi.yml
  format: yaml
  label: Scrunch AI Axp Render API
  slug: scrunch-ai-axp-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-axp-render-api-openapi.yml
- filename: scrunch-ai-brands-api-openapi.yml
  format: yaml
  label: Scrunch AI Brands API
  slug: scrunch-ai-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-brands-api-openapi.yml
- filename: scrunch-ai-orchestration-api-openapi.yml
  format: yaml
  label: Scrunch AI Orchestration API
  slug: scrunch-ai-orchestration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-orchestration-api-openapi.yml
- filename: scrunch-ai-page-audits-api-openapi.yml
  format: yaml
  label: Scrunch AI Page Audits API
  slug: scrunch-ai-page-audits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-page-audits-api-openapi.yml
- filename: scrunch-ai-prompts-api-openapi.yml
  format: yaml
  label: Scrunch AI Prompts API
  slug: scrunch-ai-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-prompts-api-openapi.yml
- filename: scrunch-ai-query-api-openapi.yml
  format: yaml
  label: Scrunch AI Query API
  slug: scrunch-ai-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-query-api-openapi.yml
- filename: scrunch-ai-responses-api-openapi.yml
  format: yaml
  label: Scrunch AI Responses API
  slug: scrunch-ai-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-responses-api-openapi.yml
- filename: scrunch-ai-sitemap-api-openapi.yml
  format: yaml
  label: Scrunch AI Sitemap API
  slug: scrunch-ai-sitemap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-sitemap-api-openapi.yml
- filename: scrunch-ai-signals-api-openapi.yml
  format: yaml
  label: Scrunch AI Signals API
  slug: scrunch-ai-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-signals-api-openapi.yml
- filename: scrunch-ai-collections-api-openapi.yml
  format: yaml
  label: Scrunch AI Collections API
  slug: scrunch-ai-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-collections-api-openapi.yml
- filename: scrunch-ai-scrunch-data-api-api-openapi.yml
  format: yaml
  label: Scrunch AI Scrunch Data API
  slug: scrunch-ai-scrunch-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrunch-ai/openapi/scrunch-ai-scrunch-data-api-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Services may not be used in or for the benefit of, or exported or re-exported to (a) any U.S. embargoed country or territory or (b) any individual or entity with whom dealings are prohibited or restricted under applicable trade laws.
  entity_types:
  - text: You may use this Site provided that (i) you are over 18 years of age
    type: individual
  - text: These Terms of Use apply to all users, including commercial users, unless you have entered into a separate agreement with Scrunch AI
    type: business
  minimum_age:
    text: you are over 18 years of age
    value: '18'
  restricted_uses:
  - summary: Decisions about individuals
    text: You must not use any Output relating to a person for any purpose that could have a legal or material impact on that person, such as making credit, educational, employment, housing, insurance, legal, medical, or other important decisions about them
  - summary: Children's personal information
    text: send us any personal information of children under 13 or the applicable age of digital consent or allow minors to use the Services without consent from their parent or guardian;
  - summary: Trade sanctions and export controls
    text: You must comply with all applicable trade laws, including sanctions and export control laws.
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
name: Scrunch AI
provenance_date: '2026-11-10'
provider_name: Scrunch AI
provider_slug: scrunch-ai
slug: scrunch-ai-eligibility
source_date: '2026-11-10'
source_filename: scrunch-ai-eligibility.yml
source_heading: Eligibility
source_page: https://scrunch.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scrunch AI\naid: scrunch-ai\nurl: https://scrunch.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our Services may not be used in or for the benefit of, or exported or re-exported to (a) any U.S. embargoed\n    country or territory or (b) any individual or entity with whom dealings are prohibited or restricted under applicable\n    trade laws.\nentity_types:\n- type: individual\n  text: You may use this Site provided that (i) you are over 18 years of age\n- type: business\n  text: These Terms of Use apply to all users, including commercial users, unless you have entered\
  \ into a separate\n    agreement with Scrunch AI\nrestricted_uses:\n- summary: Decisions about individuals\n  text: You must not use any Output relating to a person for any purpose that could have a legal or material impact\n    on that person, such as making credit, educational, employment, housing, insurance, legal, medical, or other\n    important decisions about them\n- summary: Children's personal information\n  text: send us any personal information of children under 13 or the applicable age of digital consent or allow\n    minors to use the Services without consent from their parent or guardian;\n- summary: Trade sanctions and export controls\n  text: You must comply with all applicable trade laws, including sanctions and export control laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/scrunch-ai/eligibility/scrunch-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Scrunch AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Search
- Answer Engine Optimization
- Generative Engine Optimization
- Brand Visibility
- Analytics
- SEO
- Agent Experience
- MCP
---
