---
api_specs:
- filename: goethena-learner-training-campaigns-api-openapi.yml
  format: yaml
  label: Goethena Learner Training Campaigns API
  slug: goethena-learner-training-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goethena/openapi/goethena-learner-training-campaigns-api-openapi.yml
- filename: goethena-learner-training-modules-api-openapi.yml
  format: yaml
  label: Goethena Learner Training Modules API
  slug: goethena-learner-training-modules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goethena/openapi/goethena-learner-training-modules-api-openapi.yml
- filename: goethena-learners-api-openapi.yml
  format: yaml
  label: Goethena Learners API
  slug: goethena-learners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goethena/openapi/goethena-learners-api-openapi.yml
- filename: goethena-training-campaigns-api-openapi.yml
  format: yaml
  label: Goethena Training Campaigns API
  slug: goethena-training-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goethena/openapi/goethena-training-campaigns-api-openapi.yml
- filename: goethena-webhooks-api-openapi.yml
  format: yaml
  label: Goethena Webhooks API
  slug: goethena-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goethena/openapi/goethena-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: our Services are designed for business customers
    type: business
  minimum_age:
    text: null
    value: null
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
name: Goethena
provenance_date: '2026-11-09'
provider_name: Goethena
provider_slug: goethena
slug: goethena-eligibility
source_date: '2026-11-09'
source_filename: goethena-eligibility.yml
source_heading: Eligibility
source_page: https://www.goethena.com/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goethena\naid: goethena\nurl: https://www.goethena.com/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: our Services are designed for business customers\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/goethena/eligibility/goethena-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Goethena's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- Training
- Human Resources
- Ethics
- LMS
- AI Agents
- Governance
- Workforce
- Governance Risk and Compliance
- Workflows
- Webhook
---
