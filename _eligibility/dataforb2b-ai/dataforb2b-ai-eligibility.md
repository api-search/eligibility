---
api_specs:
- filename: dataforb2b-ai-dataforb2b-api-api-openapi.yml
  format: yaml
  label: dataforb2b-ai DataForB2B API
  slug: dataforb2b-ai-dataforb2b-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforb2b-ai/openapi/dataforb2b-ai-dataforb2b-api-api-openapi.yml
- filename: dataforb2b-ai-health-api-openapi.yml
  format: yaml
  label: dataforb2b-ai Health API
  slug: dataforb2b-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforb2b-ai/openapi/dataforb2b-ai-health-api-openapi.yml
- filename: dataforb2b-ai-search-api-openapi.yml
  format: yaml
  label: dataforb2b-ai Search API
  slug: dataforb2b-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforb2b-ai/openapi/dataforb2b-ai-search-api-openapi.yml
- filename: dataforb2b-ai-stats-api-openapi.yml
  format: yaml
  label: dataforb2b-ai Stats API
  slug: dataforb2b-ai-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforb2b-ai/openapi/dataforb2b-ai-stats-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services in any country subject to trade sanctions.
  entity_types:
  - text: Access and use the Platform and Services for your internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: FCRA and consumer credit uses
    text: Use the Services for consumer marketing, credit decisions, or any purpose covered by the Fair Credit Reporting Act ("FCRA"), including establishing an individual's eligibility for credit, insurance, housing, or government benefits
  - summary: Employment decisions
    text: Use the Services or data obtained through them as a factor in deciding whether to hire, promote, reassign, or retain an individual, including screening job applicants
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
name: dataforb2b-ai
provenance_date: '2026-11-09'
provider_name: dataforb2b-ai
provider_slug: dataforb2b-ai
slug: dataforb2b-ai-eligibility
source_date: '2026-11-09'
source_filename: dataforb2b-ai-eligibility.yml
source_heading: Eligibility
source_page: https://dataforb2b.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dataforb2b-ai\naid: dataforb2b-ai\nurl: https://dataforb2b.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services in any country subject to trade sanctions.\nentity_types:\n- type: business\n  text: Access and use the Platform and Services for your internal business purposes\nrestricted_uses:\n- summary: FCRA and consumer credit uses\n  text: Use the Services for consumer marketing, credit decisions, or any purpose covered by the Fair Credit Reporting\n    Act (\"FCRA\"), including establishing an individual's eligibility for credit, insurance, housing,\
  \ or government\n    benefits\n- summary: Employment decisions\n  text: Use the Services or data obtained through them as a factor in deciding whether to hire, promote, reassign,\n    or retain an individual, including screening job applicants\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dataforb2b-ai/eligibility/dataforb2b-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from dataforb2b-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- B2B
- Artificial Intelligence
- Analytics
---
