---
api_specs:
- filename: amazon-sqs-messages-api-openapi.yml
  format: yaml
  label: Amazon SQS Messages API
  slug: amazon-sqs-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-sqs/openapi/amazon-sqs-messages-api-openapi.yml
- filename: amazon-sqs-permissions-api-openapi.yml
  format: yaml
  label: Amazon SQS Permissions API
  slug: amazon-sqs-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-sqs/openapi/amazon-sqs-permissions-api-openapi.yml
- filename: amazon-sqs-queues-api-openapi.yml
  format: yaml
  label: Amazon SQS Queues API
  slug: amazon-sqs-queues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-sqs/openapi/amazon-sqs-queues-api-openapi.yml
- filename: amazon-sqs-tags-api-openapi.yml
  format: yaml
  label: Amazon SQS Tags API
  slug: amazon-sqs-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-sqs/openapi/amazon-sqs-tags-api-openapi.yml
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
  - summary: Cryptocurrency mining
    text: You will not use, and will not facilitate or allow End Users to use, the Services to mine cryptocurrency.
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
name: Amazon SQS
provenance_date: '2026-11-09'
provider_name: Amazon SQS
provider_slug: amazon-sqs
slug: amazon-sqs-eligibility
source_date: '2026-11-09'
source_filename: amazon-sqs-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon SQS\naid: amazon-sqs\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Cryptocurrency mining\n  text: You will not use, and will not facilitate or allow End Users to use, the Services to mine cryptocurrency.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-sqs/eligibility/amazon-sqs-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amazon SQS's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Cloud
- Distributed Systems
- Messaging
- Microservices
- Queues
---
