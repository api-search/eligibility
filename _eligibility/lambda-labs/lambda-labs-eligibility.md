---
api_specs:
- filename: lambda-labs-asyncapi.yml
  format: yaml
  label: Lambda Inference API
  slug: inference-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/lambda-labs/asyncapi/lambda-labs-asyncapi.yml
- filename: lambda-labs-audit-events-api-openapi.yml
  format: yaml
  label: Lambda Audit Events API
  slug: lambda-labs-audit-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lambda-labs/openapi/lambda-labs-audit-events-api-openapi.yml
- filename: lambda-labs-fabric-api-openapi.yml
  format: yaml
  label: Lambda Fabric API
  slug: lambda-labs-fabric-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lambda-labs/openapi/lambda-labs-fabric-api-openapi.yml
- filename: lambda-labs-filesystems-api-openapi.yml
  format: yaml
  label: Lambda Filesystems API
  slug: lambda-labs-filesystems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lambda-labs/openapi/lambda-labs-filesystems-api-openapi.yml
- filename: lambda-labs-firewalls-api-openapi.yml
  format: yaml
  label: Lambda Firewalls API
  slug: lambda-labs-firewalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lambda-labs/openapi/lambda-labs-firewalls-api-openapi.yml
- filename: lambda-labs-images-api-openapi.yml
  format: yaml
  label: Lambda Images API
  slug: lambda-labs-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lambda-labs/openapi/lambda-labs-images-api-openapi.yml
- filename: lambda-labs-instances-api-openapi.yml
  format: yaml
  label: Lambda Instances API
  slug: lambda-labs-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lambda-labs/openapi/lambda-labs-instances-api-openapi.yml
- filename: lambda-labs-regions-api-openapi.yml
  format: yaml
  label: Lambda Regions API
  slug: lambda-labs-regions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lambda-labs/openapi/lambda-labs-regions-api-openapi.yml
- filename: lambda-labs-ssh-keys-api-openapi.yml
  format: yaml
  label: Lambda SSH keys API
  slug: lambda-labs-ssh-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lambda-labs/openapi/lambda-labs-ssh-keys-api-openapi.yml
- filename: lambda-labs-support-tickets-api-openapi.yml
  format: yaml
  label: Lambda Support Tickets API
  slug: lambda-labs-support-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lambda-labs/openapi/lambda-labs-support-tickets-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not export or provide access to the Sites into any U.S. embargoed countries
  entity_types:
  - text: whether you are an individual user
    type: individual
  - text: a user on behalf of a company or team
    type: business
  minimum_age:
    text: you must be a natural person of at least age 13
    value: '13'
  restricted_uses:
  - summary: Evaluation use non-commercial only
    text: Use of our Services for evaluation purposes are for your personal, non-commercial use only.
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
name: Lambda
provenance_date: '2026-11-09'
provider_name: Lambda
provider_slug: lambda-labs
slug: lambda-labs-eligibility
source_date: '2026-11-09'
source_filename: lambda-labs-eligibility.yml
source_heading: Eligibility
source_page: https://lambda.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lambda\naid: lambda-labs\nurl: https://lambda.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may not export or provide access to the Sites into any U.S. embargoed countries\nentity_types:\n- type: individual\n  text: whether you are an individual user\n- type: business\n  text: a user on behalf of a company or team\nrestricted_uses:\n- summary: Evaluation use non-commercial only\n  text: Use of our Services for evaluation purposes are for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: you must be a natural person of at least age 13\n"
source_yaml_url: https://artifacts.apis.io/lambda-labs/eligibility/lambda-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Lambda's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Cloud
- Cluster
- Compute
- GPU
- Inference
- Machine Learning
- Real-Time
---
