---
api_specs:
- filename: aws-lambda-aliases-api-openapi.yml
  format: yaml
  label: AWS Lambda Aliases API
  slug: aws-lambda-aliases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-aliases-api-openapi.yml
- filename: aws-lambda-concurrency-api-openapi.yml
  format: yaml
  label: AWS Lambda Concurrency API
  slug: aws-lambda-concurrency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-concurrency-api-openapi.yml
- filename: aws-lambda-event-source-mappings-api-openapi.yml
  format: yaml
  label: AWS Lambda Event Source Mappings API
  slug: aws-lambda-event-source-mappings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-event-source-mappings-api-openapi.yml
- filename: aws-lambda-function-url-api-openapi.yml
  format: yaml
  label: AWS Lambda Function URL API
  slug: aws-lambda-function-url-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-function-url-api-openapi.yml
- filename: aws-lambda-functions-api-openapi.yml
  format: yaml
  label: AWS Lambda Functions API
  slug: aws-lambda-functions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-functions-api-openapi.yml
- filename: aws-lambda-layers-api-openapi.yml
  format: yaml
  label: AWS Lambda Layers API
  slug: aws-lambda-layers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-layers-api-openapi.yml
- filename: aws-lambda-tags-api-openapi.yml
  format: yaml
  label: AWS Lambda Tags API
  slug: aws-lambda-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-tags-api-openapi.yml
- filename: aws-lambda-versions-api-openapi.yml
  format: yaml
  label: AWS Lambda Versions API
  slug: aws-lambda-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-versions-api-openapi.yml
- filename: aws-lambda-capacity-providers-api-openapi.yml
  format: yaml
  label: AWS Lambda Lambda Capacity Providers API
  slug: aws-lambda-capacity-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-capacity-providers-api-openapi.yml
- filename: aws-lambda-code-signing-config-api-openapi.yml
  format: yaml
  label: AWS Lambda Lambda Code Signing Config API
  slug: aws-lambda-code-signing-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-code-signing-config-api-openapi.yml
- filename: aws-lambda-event-invoke-config-api-openapi.yml
  format: yaml
  label: AWS Lambda Lambda Event Invoke Config API
  slug: aws-lambda-event-invoke-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-event-invoke-config-api-openapi.yml
- filename: aws-lambda-operations-api-openapi.yml
  format: yaml
  label: AWS Lambda Lambda Operations API
  slug: aws-lambda-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-operations-api-openapi.yml
- filename: aws-lambda-policy-api-openapi.yml
  format: yaml
  label: AWS Lambda Lambda Policy API
  slug: aws-lambda-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-policy-api-openapi.yml
- filename: aws-lambda-provisioned-concurrency-api-openapi.yml
  format: yaml
  label: AWS Lambda Lambda Provisioned Concurrency API
  slug: aws-lambda-provisioned-concurrency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-provisioned-concurrency-api-openapi.yml
- filename: aws-lambda-resource-policy-api-openapi.yml
  format: yaml
  label: AWS Lambda Lambda Resource Policy API
  slug: aws-lambda-resource-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-lambda/openapi/aws-lambda-resource-policy-api-openapi.yml
claim_count: 2
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
  - summary: Microsoft Software high-risk use
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other modes of human mass transportation, nuclear or chemical facilities, life support systems
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
name: AWS Lambda
provenance_date: '2026-11-09'
provider_name: AWS Lambda
provider_slug: aws-lambda
slug: aws-lambda-eligibility
source_date: '2026-11-09'
source_filename: aws-lambda-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AWS Lambda\naid: aws-lambda\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spend limits not for critical systems\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems\n- summary: Microsoft Software high-risk use\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other\n    modes of human mass transportation,\
  \ nuclear or chemical facilities, life support systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aws-lambda/eligibility/aws-lambda-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from AWS Lambda's own page on 2026-11-09.
synthetic: false
tags:
- Serverless
- Monitoring
- Observability
- Logging
- Telemetry
- AWS Lambda
---
