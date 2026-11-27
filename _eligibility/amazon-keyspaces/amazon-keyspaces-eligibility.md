---
api_specs:
- filename: amazon-keyspaces-keyspaces-api-openapi.yml
  format: yaml
  label: Amazon Keyspaces API
  slug: amazon-keyspaces-keyspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-keyspaces/openapi/amazon-keyspaces-keyspaces-api-openapi.yml
- filename: amazon-keyspaces-tables-api-openapi.yml
  format: yaml
  label: Amazon Keyspaces Tables API
  slug: amazon-keyspaces-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-keyspaces/openapi/amazon-keyspaces-tables-api-openapi.yml
- filename: amazon-keyspaces-operations-api-openapi.yml
  format: yaml
  label: Amazon Keyspaces Keyspaces Operations API
  slug: amazon-keyspaces-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-keyspaces/openapi/amazon-keyspaces-operations-api-openapi.yml
- filename: amazon-keyspaces-type-api-openapi.yml
  format: yaml
  label: Amazon Keyspaces Keyspaces Type API
  slug: amazon-keyspaces-type-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-keyspaces/openapi/amazon-keyspaces-type-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spend limits not for critical systems
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems
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
name: Amazon Keyspaces
provenance_date: '2026-11-09'
provider_name: Amazon Keyspaces
provider_slug: amazon-keyspaces
slug: amazon-keyspaces-eligibility
source_date: '2026-11-09'
source_filename: amazon-keyspaces-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Keyspaces\naid: amazon-keyspaces\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spend limits not for critical systems\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-keyspaces/eligibility/amazon-keyspaces-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amazon Keyspaces's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Cassandra
- Database
- Managed Database
- NoSQL
- Wide Column
---
