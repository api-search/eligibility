---
api_specs:
- filename: lucent-insights-api-openapi.yml
  format: yaml
  label: Lucent Insights API
  slug: lucent-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucent/openapi/lucent-insights-api-openapi.yml
- filename: lucent-issues-api-openapi.yml
  format: yaml
  label: Lucent Issues API
  slug: lucent-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucent/openapi/lucent-issues-api-openapi.yml
- filename: lucent-sdk-api-openapi.yml
  format: yaml
  label: Lucent Sdk API
  slug: lucent-sdk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucent/openapi/lucent-sdk-api-openapi.yml
- filename: lucent-signals-api-openapi.yml
  format: yaml
  label: Lucent Signals API
  slug: lucent-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucent/openapi/lucent-signals-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you signed up for a plan using your corporate email domain or are otherwise entering into a plan on behalf of a business entity or other organization, the business entity or other organization on whose behalf you signed up is the Customer.
    type: business
  - text: '"Customer" or "you" is either you, if you are an individual entering into the Agreement on your own behalf'
    type: individual
  minimum_age:
    text: any access to, or use of, the Services by anyone who is a minor (which is under the age of 18 in most jurisdictions) in any applicable jurisdiction is strictly prohibited
    value: '18'
  restricted_uses:
  - summary: Commercial solicitation
    text: using the Services for any commercial solicitation purposes
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
name: Lucent
provenance_date: '2026-11-09'
provider_name: Lucent
provider_slug: lucent
slug: lucent-eligibility
source_date: '2026-11-09'
source_filename: lucent-eligibility.yml
source_heading: Eligibility
source_page: https://lucenthq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lucent\naid: lucent\nurl: https://lucenthq.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you signed up for a plan using your corporate email domain or are otherwise entering into a plan on behalf\n    of a business entity or other organization, the business entity or other organization on whose behalf you signed\n    up is the Customer.\n- type: individual\n  text: '\"Customer\" or \"you\" is either you, if you are an individual entering into the Agreement on your own behalf'\nrestricted_uses:\n- summary: Commercial solicitation\n\
  \  text: using the Services for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: any access to, or use of, the Services by anyone who is a minor (which is under the age of 18 in most jurisdictions)\n    in any applicable jurisdiction is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/lucent/eligibility/lucent-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lucent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Session Replay
- Product Analytics
- Bug Detection
- Observability
- Artificial Intelligence
- Developer Tools
- MCP
- Webhook
---
