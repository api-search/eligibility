---
api_specs:
- filename: replicate-accounts-api-openapi.yml
  format: yaml
  label: Replicate Accounts API
  slug: replicate-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-accounts-api-openapi.yml
- filename: replicate-cancel-api-openapi.yml
  format: yaml
  label: Replicate Cancel API
  slug: replicate-cancel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-cancel-api-openapi.yml
- filename: replicate-collections-api-openapi.yml
  format: yaml
  label: Replicate Collections API
  slug: replicate-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-collections-api-openapi.yml
- filename: replicate-deployments-api-openapi.yml
  format: yaml
  label: Replicate Deployments API
  slug: replicate-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-deployments-api-openapi.yml
- filename: replicate-hardware-api-openapi.yml
  format: yaml
  label: Replicate Hardware API
  slug: replicate-hardware-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-hardware-api-openapi.yml
- filename: replicate-model-api-openapi.yml
  format: yaml
  label: Replicate Model API
  slug: replicate-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-model-api-openapi.yml
- filename: replicate-models-api-openapi.yml
  format: yaml
  label: Replicate Models API
  slug: replicate-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-models-api-openapi.yml
- filename: replicate-predictions-api-openapi.yml
  format: yaml
  label: Replicate Predictions API
  slug: replicate-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-predictions-api-openapi.yml
- filename: replicate-secrets-api-openapi.yml
  format: yaml
  label: Replicate Secrets API
  slug: replicate-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-secrets-api-openapi.yml
- filename: replicate-training-api-openapi.yml
  format: yaml
  label: Replicate Training API
  slug: replicate-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-training-api-openapi.yml
- filename: replicate-trainings-api-openapi.yml
  format: yaml
  label: Replicate Trainings API
  slug: replicate-trainings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-trainings-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not eligible to be a Customer either directly or indirectly if you are barred from using the Services under the Laws of the United States or any other applicable jurisdiction
  entity_types:
  - text: the end user in your personal capacity who is utilizing the Services
    type: individual
  - text: in case you are acting as a duly authorized Representative (as defined) of an entity, the reference shall mean such entity
    type: business
  minimum_age:
    text: you are at least 18 years of age or over the age of majority in the jurisdiction where you are a resident or citizen
    value: '18'
  restricted_uses:
  - summary: Prohibited harmful content and activities
    text: 'to commit, promote, contribute to, facilitate, encourage, plan, incite, or further any of the following: a. violence, terrorism or generation of hateful content'
  - summary: Fully automated decision-making with legal effects
    text: 'for purposes of or for the performance of: a. fully automated decision-making, including profiling, with respect to an individual or group of individuals which produces legal effects concerning such individual(s)'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use our Services, you must sign on to Replicate using your GitHub account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Replicate
provenance_date: '2026-11-10'
provider_name: Replicate
provider_slug: replicate
slug: replicate-eligibility
source_date: '2026-11-10'
source_filename: replicate-eligibility.yml
source_heading: Eligibility
source_page: https://replicate.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Replicate\naid: replicate\nurl: https://replicate.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You are not eligible to be a Customer either directly or indirectly if you are barred from using the Services\n    under the Laws of the United States or any other applicable jurisdiction\nentity_types:\n- type: individual\n  text: the end user in your personal capacity who is utilizing the Services\n- type: business\n  text: in case you are acting as a duly authorized Representative (as defined) of an entity, the reference shall\n    mean such entity\nrestricted_uses:\n\
  - summary: Prohibited harmful content and activities\n  text: 'to commit, promote, contribute to, facilitate, encourage, plan, incite, or further any of the following:\n    a. violence, terrorism or generation of hateful content'\n- summary: Fully automated decision-making with legal effects\n  text: 'for purposes of or for the performance of: a. fully automated decision-making, including profiling, with\n    respect to an individual or group of individuals which produces legal effects concerning such individual(s)'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use our Services, you must sign on to Replicate using your GitHub account\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age or over the age of majority in the jurisdiction where you are a resident\n    or citizen\n"
source_yaml_url: https://artifacts.apis.io/replicate/eligibility/replicate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Replicate's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Image Generation
- Language Models
- Model Deployment
- Inference
---
