---
api_specs:
- filename: amazon-fargate-account-settings-api-openapi.yml
  format: yaml
  label: Amazon Fargate Account Settings API
  slug: amazon-fargate-account-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-fargate/openapi/amazon-fargate-account-settings-api-openapi.yml
- filename: amazon-fargate-clusters-api-openapi.yml
  format: yaml
  label: Amazon Fargate Clusters API
  slug: amazon-fargate-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-fargate/openapi/amazon-fargate-clusters-api-openapi.yml
- filename: amazon-fargate-services-api-openapi.yml
  format: yaml
  label: Amazon Fargate Services API
  slug: amazon-fargate-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-fargate/openapi/amazon-fargate-services-api-openapi.yml
- filename: amazon-fargate-tagging-api-openapi.yml
  format: yaml
  label: Amazon Fargate Tagging API
  slug: amazon-fargate-tagging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-fargate/openapi/amazon-fargate-tagging-api-openapi.yml
- filename: amazon-fargate-task-definitions-api-openapi.yml
  format: yaml
  label: Amazon Fargate Task Definitions API
  slug: amazon-fargate-task-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-fargate/openapi/amazon-fargate-task-definitions-api-openapi.yml
- filename: amazon-fargate-tasks-api-openapi.yml
  format: yaml
  label: Amazon Fargate Tasks API
  slug: amazon-fargate-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-fargate/openapi/amazon-fargate-tasks-api-openapi.yml
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
  - summary: Microsoft Software in high-risk applications
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft
  - summary: Spend limits in hazardous or critical systems
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
name: Amazon Fargate
provenance_date: '2026-11-09'
provider_name: Amazon Fargate
provider_slug: amazon-fargate
slug: amazon-fargate-eligibility
source_date: '2026-11-09'
source_filename: amazon-fargate-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Fargate\naid: amazon-fargate\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Microsoft Software in high-risk applications\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft\n- summary: Spend limits in hazardous or critical systems\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-fargate/eligibility/amazon-fargate-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Amazon Fargate's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Compute
- Containers
- ECS
- EKS
- Microservices
- Serverless
---
