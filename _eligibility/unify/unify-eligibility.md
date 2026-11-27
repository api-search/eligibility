---
api_specs:
- filename: unify-events-api-openapi.yml
  format: yaml
  label: Unify Analytics Events API
  slug: unify-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unify/openapi/unify-events-api-openapi.yml
- filename: unify-sequences-api-openapi.yml
  format: yaml
  label: Unify Sequences API
  slug: unify-sequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unify/openapi/unify-sequences-api-openapi.yml
- filename: unify-tasks-api-openapi.yml
  format: yaml
  label: Unify Tasks API
  slug: unify-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unify/openapi/unify-tasks-api-openapi.yml
- filename: unify-data-api-openapi.yml
  format: yaml
  label: Unify Data API
  slug: unify-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unify/openapi/unify-data-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement (“ Customer ”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer credit, insurance, employment or government eligibility
    text: (l) use the Services to determine a consumer’s eligibility for credit or insurance for personal, family or household purposes, employment, a government license or benefit, or any other purpose governed or regulated by the Fair Credit Reporting Act
  - summary: Life-critical or safety-critical use
    text: (m) use any Unify IP for any activity where use or failure of the Unify IP could lead to death, personal injury or environmental damage
  - summary: Political and intelligence uses
    text: (o) leverage the Services to support or benefit any specific political candidate, party, campaign, or affiliated advocacy group
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
name: Unify
provenance_date: '2026-11-10'
provider_name: Unify
provider_slug: unify
slug: unify-eligibility
source_date: '2026-11-10'
source_filename: unify-eligibility.yml
source_heading: Eligibility
source_page: https://www.unifygtm.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unify\naid: unify\nurl: https://www.unifygtm.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement (“ Customer ”)\nrestricted_uses:\n- summary: Consumer credit, insurance, employment or government eligibility\n  text: (l) use the Services to determine a consumer’s eligibility for credit or insurance for personal, family\n    or household purposes, employment, a government license or benefit, or any other purpose governed\
  \ or regulated\n    by the Fair Credit Reporting Act\n- summary: Life-critical or safety-critical use\n  text: (m) use any Unify IP for any activity where use or failure of the Unify IP could lead to death, personal\n    injury or environmental damage\n- summary: Political and intelligence uses\n  text: (o) leverage the Services to support or benefit any specific political candidate, party, campaign, or affiliated\n    advocacy group\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unify/eligibility/unify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Unify's own page on 2026-11-10.
synthetic: false
tags:
- Sales
- Marketing
- Go-To-Market
- Outbound
- Intent Data
- AI Agents
- B2B
- Data Enrichment
- Sequences
- Analytics
- Task
- Bulk API
- MCP
- Agent Skills
- Webhook
- A2A
---
