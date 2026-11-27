---
api_specs:
- filename: sharethis-ai-summary-api-openapi.yml
  format: yaml
  label: ShareThis AI Summary API
  slug: sharethis-ai-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharethis/openapi/sharethis-ai-summary-api-openapi.yml
- filename: sharethis-apps-api-openapi.yml
  format: yaml
  label: ShareThis Apps API
  slug: sharethis-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharethis/openapi/sharethis-apps-api-openapi.yml
- filename: sharethis-audience-api-openapi.yml
  format: yaml
  label: ShareThis Audience API
  slug: sharethis-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharethis/openapi/sharethis-audience-api-openapi.yml
- filename: sharethis-authentication-api-openapi.yml
  format: yaml
  label: ShareThis Authentication API
  slug: sharethis-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharethis/openapi/sharethis-authentication-api-openapi.yml
- filename: sharethis-oauth-clients-api-openapi.yml
  format: yaml
  label: ShareThis OAuth Clients API
  slug: sharethis-oauth-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharethis/openapi/sharethis-oauth-clients-api-openapi.yml
- filename: sharethis-properties-api-openapi.yml
  format: yaml
  label: ShareThis Properties API
  slug: sharethis-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharethis/openapi/sharethis-properties-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Neither the ShareThis Publisher Applications nor the underlying information or technology may be downloaded or otherwise provided or made available, either directly or indirectly, into any country subject to U.S. trade sanctions
  entity_types:
  - text: individuals who are legally capable of entering into contracts (i.e., eighteen (18) years of age or older in most places)
    type: individual
  - text: corporations and other legal entities authorized to form legally binding contracts under applicable law
    type: business
  minimum_age:
    text: eighteen (18) years of age or older in most places
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must register with Us to use the ShareThis Publisher Applications on Your Publisher Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ShareThis
provenance_date: '2026-11-10'
provider_name: ShareThis
provider_slug: sharethis
slug: sharethis-eligibility
source_date: '2026-11-10'
source_filename: sharethis-eligibility.yml
source_heading: Eligibility
source_page: https://sharethis.com/publisher-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShareThis\naid: sharethis\nurl: https://sharethis.com/publisher-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Neither the ShareThis Publisher Applications nor the underlying information or technology may be downloaded\n    or otherwise provided or made available, either directly or indirectly, into any country subject to U.S. trade\n    sanctions\nentity_types:\n- type: individual\n  text: individuals who are legally capable of entering into contracts (i.e., eighteen (18) years of age or older\n    in most places)\n- type: business\n  text: corporations\
  \ and other legal entities authorized to form legally binding contracts under applicable law\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must register with Us to use the ShareThis Publisher Applications on Your Publisher Site.\nminimum_age:\n  value: '18'\n  text: eighteen (18) years of age or older in most places\n"
source_yaml_url: https://artifacts.apis.io/sharethis/eligibility/sharethis-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from ShareThis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Sharing
- Website Tools
- Audience Data
- AdTech
- Analytics
- Consent Management
- Publishing
- MCP
---
