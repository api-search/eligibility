---
api_specs:
- filename: arcmira-channels-api-openapi.yml
  format: yaml
  label: Arcmira Channels API
  slug: arcmira-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-channels-api-openapi.yml
- filename: arcmira-entities-api-openapi.yml
  format: yaml
  label: Arcmira Entities API
  slug: arcmira-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-entities-api-openapi.yml
- filename: arcmira-feedback-api-openapi.yml
  format: yaml
  label: Arcmira Feedback API
  slug: arcmira-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-feedback-api-openapi.yml
- filename: arcmira-mentions-api-openapi.yml
  format: yaml
  label: Arcmira Mentions API
  slug: arcmira-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-mentions-api-openapi.yml
- filename: arcmira-meta-api-openapi.yml
  format: yaml
  label: Arcmira Meta API
  slug: arcmira-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-meta-api-openapi.yml
- filename: arcmira-monitors-api-openapi.yml
  format: yaml
  label: Arcmira Monitors API
  slug: arcmira-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-monitors-api-openapi.yml
- filename: arcmira-recommendations-api-openapi.yml
  format: yaml
  label: Arcmira Recommendations API
  slug: arcmira-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-recommendations-api-openapi.yml
- filename: arcmira-search-api-openapi.yml
  format: yaml
  label: Arcmira Search API
  slug: arcmira-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-search-api-openapi.yml
- filename: arcmira-trackers-api-openapi.yml
  format: yaml
  label: Arcmira Trackers API
  slug: arcmira-trackers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-trackers-api-openapi.yml
- filename: arcmira-transcriptions-api-openapi.yml
  format: yaml
  label: Arcmira Transcriptions API
  slug: arcmira-transcriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-transcriptions-api-openapi.yml
- filename: arcmira-transcripts-api-openapi.yml
  format: yaml
  label: Arcmira Transcripts API
  slug: arcmira-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-transcripts-api-openapi.yml
- filename: arcmira-channels-api-openapi.yml
  format: yaml
  label: Arcmira Channels API
  slug: arcmira-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcmira/openapi/arcmira-channels-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services in violation of US export control or sanctions laws, and you represent that you are not located in an embargoed country or on any restricted party list.
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract to use the Services.
    type: individual
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization, and "you" refers to both you and that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to use the Services.
    value: '18'
  restricted_uses:
  - summary: Competing product development
    text: use the Services to develop a competing product
  - summary: Violating law or rights
    text: use the Services or Output to violate any law or regulation, to infringe or violate the rights of any person
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
name: Arcmira
provenance_date: '2026-11-09'
provider_name: Arcmira
provider_slug: arcmira
slug: arcmira-eligibility
source_date: '2026-11-09'
source_filename: arcmira-eligibility.yml
source_heading: Eligibility
source_page: https://arcmira.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arcmira\naid: arcmira\nurl: https://arcmira.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services in violation of US export control or sanctions laws, and you represent that\n    you are not located in an embargoed country or on any restricted party list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Services.\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization, and \"\
  you\" refers to both you and that organization.\nrestricted_uses:\n- summary: Competing product development\n  text: use the Services to develop a competing product\n- summary: Violating law or rights\n  text: use the Services or Output to violate any law or regulation, to infringe or violate the rights of any person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/arcmira/eligibility/arcmira-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Arcmira's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Search
- YouTube
- Transcripts
- SDK
---
