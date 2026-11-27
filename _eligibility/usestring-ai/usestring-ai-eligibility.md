---
api_specs:
- filename: usestring-ai-browser-api-openapi.yml
  format: yaml
  label: usestring-ai Browser API
  slug: usestring-ai-browser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-browser-api-openapi.yml
- filename: usestring-ai-builds-api-openapi.yml
  format: yaml
  label: usestring-ai Builds API
  slug: usestring-ai-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-builds-api-openapi.yml
- filename: usestring-ai-contexts-api-openapi.yml
  format: yaml
  label: usestring-ai Contexts API
  slug: usestring-ai-contexts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-contexts-api-openapi.yml
- filename: usestring-ai-documentation-api-openapi.yml
  format: yaml
  label: usestring-ai Documentation API
  slug: usestring-ai-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-documentation-api-openapi.yml
- filename: usestring-ai-feeds-api-openapi.yml
  format: yaml
  label: usestring-ai Feeds API
  slug: usestring-ai-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-feeds-api-openapi.yml
- filename: usestring-ai-fetch-api-openapi.yml
  format: yaml
  label: usestring-ai Fetch API
  slug: usestring-ai-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-fetch-api-openapi.yml
- filename: usestring-ai-search-api-openapi.yml
  format: yaml
  label: usestring-ai Search API
  slug: usestring-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-search-api-openapi.yml
- filename: usestring-ai-sessions-api-openapi.yml
  format: yaml
  label: usestring-ai Sessions API
  slug: usestring-ai-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-sessions-api-openapi.yml
- filename: usestring-ai-sitemap-api-openapi.yml
  format: yaml
  label: usestring-ai Sitemap API
  slug: usestring-ai-sitemap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-sitemap-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Restricted destination categories
    text: Some destination categories are restricted by default and require approval before access.
  - summary: Circumventing authentication of systems not owned
    text: use the Services to circumvent authentication on any system you do not own or are not authorized to test
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
name: String
provenance_date: '2026-11-10'
provider_name: String
provider_slug: usestring-ai
slug: usestring-ai-eligibility
source_date: '2026-11-10'
source_filename: usestring-ai-eligibility.yml
source_heading: Eligibility
source_page: https://usestring.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: String\naid: usestring-ai\nurl: https://usestring.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization\nrestricted_uses:\n- summary: Restricted destination categories\n  text: Some destination categories are restricted by default and require approval before access.\n- summary: Circumventing authentication of systems\
  \ not owned\n  text: use the Services to circumvent authentication on any system you do not own or are not authorized to test\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/usestring-ai/eligibility/usestring-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from String's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- Data Extraction
- Markdown
- JSON
---
