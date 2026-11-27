---
api_specs:
- filename: tollbit-auth-tokens-api-openapi.yml
  format: yaml
  label: Tollbit Auth Tokens API
  slug: tollbit-auth-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tollbit/openapi/tollbit-auth-tokens-api-openapi.yml
- filename: tollbit-dev-api-openapi.yml
  format: yaml
  label: Tollbit Dev API
  slug: tollbit-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tollbit/openapi/tollbit-dev-api-openapi.yml
- filename: tollbit-reporting-api-openapi.yml
  format: yaml
  label: Tollbit Reporting API
  slug: tollbit-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tollbit/openapi/tollbit-reporting-api-openapi.yml
- filename: tollbit-search-api-openapi.yml
  format: yaml
  label: Tollbit Search API
  slug: tollbit-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tollbit/openapi/tollbit-search-api-openapi.yml
- filename: tollbit-tollbit-content-api-openapi.yml
  format: yaml
  label: Tollbit Content API
  slug: tollbit-tollbit-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tollbit/openapi/tollbit-tollbit-content-api-openapi.yml
- filename: tollbit-tollbit-subdomain-api-openapi.yml
  format: yaml
  label: Tollbit Subdomain API
  slug: tollbit-tollbit-subdomain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tollbit/openapi/tollbit-tollbit-subdomain-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Tollbit Platform if you are a person who is barred from doing so under the laws of the United States or any other applicable jurisdiction
  entity_types:
  - text: If you are using the Tollbit Platform on behalf of a business or entity, you represent that you are authorized to bind that business or entity to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive product development
    text: use the TollBit Platform to develop or improve a product or service that is competitive to TollBit
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
name: Tollbit
provenance_date: '2026-11-10'
provider_name: Tollbit
provider_slug: tollbit
slug: tollbit-eligibility
source_date: '2026-11-10'
source_filename: tollbit-eligibility.yml
source_heading: Eligibility
source_page: https://tollbit.com/legal/developer-platform-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tollbit\naid: tollbit\nurl: https://tollbit.com/legal/developer-platform-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Tollbit Platform if you are a person who is barred from doing so under the laws of the\n    United States or any other applicable jurisdiction\nentity_types:\n- type: business\n  text: If you are using the Tollbit Platform on behalf of a business or entity, you represent that you are authorized\n    to bind that business or entity to these Terms\nrestricted_uses:\n- summary: Competitive product development\n  text: use the TollBit\
  \ Platform to develop or improve a product or service that is competitive to TollBit\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tollbit/eligibility/tollbit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Tollbit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Content Licensing
- Content Monetization
- AI Agents
- Agentic Web
- Search
- Bot Management
- Web Infrastructure
- Developer API
---
