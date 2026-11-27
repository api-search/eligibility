---
api_specs:
- filename: streamnative-cloudstreamnativeio-v1alpha1-api-openapi.yml
  format: yaml
  label: StreamNative Cloud Streamnative Io V1alpha1 API
  slug: streamnative-cloudstreamnativeio-v1alpha1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamnative/openapi/streamnative-cloudstreamnativeio-v1alpha1-api-openapi.yml
- filename: streamnative-ksn-consumer-group-api-openapi.yml
  format: yaml
  label: StreamNative Ksn Consumer Group API
  slug: streamnative-ksn-consumer-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamnative/openapi/streamnative-ksn-consumer-group-api-openapi.yml
- filename: streamnative-ksn-topics-api-openapi.yml
  format: yaml
  label: StreamNative Ksn Topics API
  slug: streamnative-ksn-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamnative/openapi/streamnative-ksn-topics-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access from territories where StreamNative Materials are illegal is strictly prohibited; no country list given.
  entity_types:
  - text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: individual
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: not stated
  restricted_uses:
  - summary: Unlawful or unauthorized purposes
    text: you will not use the Service for any illegal or unauthorized purpose
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
name: StreamNative
provenance_date: '2026-11-10'
provider_name: StreamNative
provider_slug: streamnative
slug: streamnative-eligibility
source_date: '2026-11-10'
source_filename: streamnative-eligibility.yml
source_heading: Eligibility
source_page: https://streamnative.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StreamNative\naid: streamnative\nurl: https://streamnative.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access from territories where StreamNative Materials are illegal is strictly prohibited; no country list\n    given.\nentity_types:\n- type: individual\n  text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Unlawful or unauthorized purposes\n  text: you will not use the Service for any illegal\
  \ or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: not stated\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/streamnative/eligibility/streamnative-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from StreamNative's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Streaming
- Apache Pulsar
- Apache Kafka
- Messaging
- Event Streaming
- Cloud
---
