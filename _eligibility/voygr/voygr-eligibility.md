---
api_specs:
- filename: voygr-calls-api-openapi.yml
  format: yaml
  label: Voygr Calls API
  slug: voygr-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voygr/openapi/voygr-calls-api-openapi.yml
- filename: voygr-core-api-openapi.yml
  format: yaml
  label: VOYGR Core API
  slug: voygr-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voygr/openapi/voygr-core-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Voygr Services on behalf of your company, you represent that you are authorized to enter into the Agreement on behalf of your company.
    type: business
  - text: The Agreement is entered into by and between Voygr and the entity or person accessing the Voygr Services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No calls to private individuals
    text: Customer will not knowingly or negligently use the Outbound Calling API to contact any individual in their personal capacity
  - summary: No locating private individuals
    text: will not use the Validation / Enrichment API to obtain the address or location of a private individual or residence
  - summary: No sensitive regulated data without written agreement
    text: unless Voygr has agreed in writing to process such information
  - summary: No calls in listed states
    text: Voygr does not place Calls to businesses located in Indiana, Louisiana, Minnesota, Montana, or Nebraska
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
name: VOYGR
provenance_date: '2026-11-10'
provider_name: VOYGR
provider_slug: voygr
slug: voygr-eligibility
source_date: '2026-11-10'
source_filename: voygr-eligibility.yml
source_heading: Eligibility
source_page: https://voygr.tech/terms-api/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VOYGR\naid: voygr\nurl: https://voygr.tech/terms-api/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Voygr Services on behalf of your company, you represent that you are authorized\n    to enter into the Agreement on behalf of your company.\n- type: individual\n  text: The Agreement is entered into by and between Voygr and the entity or person accessing the Voygr Services\nrestricted_uses:\n- summary: No calls to private individuals\n  text: Customer will not knowingly or negligently use the Outbound\
  \ Calling API to contact any individual in their\n    personal capacity\n- summary: No locating private individuals\n  text: will not use the Validation / Enrichment API to obtain the address or location of a private individual or\n    residence\n- summary: No sensitive regulated data without written agreement\n  text: unless Voygr has agreed in writing to process such information\n- summary: No calls in listed states\n  text: Voygr does not place Calls to businesses located in Indiana, Louisiana, Minnesota, Montana, or Nebraska\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/voygr/eligibility/voygr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 6 quoted statements, read from VOYGR's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Location Intelligence
- POI
- Data Enrichment
- Data Validation
- Geospatial
- Places
- AI Agents
- Agent Skills
- Voice AI
- Telephony
- Outbound Calls
- Business Validation
- Y Combinator
---
