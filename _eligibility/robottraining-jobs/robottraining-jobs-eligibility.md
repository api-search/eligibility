---
api_specs:
- filename: robottraining-jobs-pay-csv-api-openapi.yml
  format: yaml
  label: RobotTraining.jobs Pay.csv API
  slug: robottraining-jobs-pay-csv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robottraining-jobs/openapi/robottraining-jobs-pay-csv-api-openapi.yml
- filename: robottraining-jobs-pay-json-api-openapi.yml
  format: yaml
  label: RobotTraining.jobs Pay.json API
  slug: robottraining-jobs-pay-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robottraining-jobs/openapi/robottraining-jobs-pay-json-api-openapi.yml
- filename: robottraining-jobs-roles-json-api-openapi.yml
  format: yaml
  label: RobotTraining.jobs Roles.json API
  slug: robottraining-jobs-roles-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robottraining-jobs/openapi/robottraining-jobs-roles-json-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: When you act for a company or other organization in using the Service, you represent that you are authorized to bind it to these Terms
    type: business
  minimum_age:
    text: You must be at least the age at which your country lets you consent to the processing of your own personal data, or the age of majority there if that is higher.
    value: Age of consent or majority, whichever is higher
  restricted_uses:
  - summary: Lawful purposes only
    text: You will use the Service only for lawful purposes, and never in a way that infringes anyone else's rights or restricts or inhibits their use of the Service.
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
name: RobotTraining.jobs
provenance_date: '2026-11-10'
provider_name: RobotTraining.jobs
provider_slug: robottraining-jobs
slug: robottraining-jobs-eligibility
source_date: '2026-11-10'
source_filename: robottraining-jobs-eligibility.yml
source_heading: Eligibility
source_page: https://robottraining.jobs/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RobotTraining.jobs\naid: robottraining-jobs\nurl: https://robottraining.jobs/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: When you act for a company or other organization in using the Service, you represent that you are authorized\n    to bind it to these Terms\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You will use the Service only for lawful purposes, and never in a way that infringes anyone else's rights\n    or restricts or inhibits their use of the Service.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: Age of consent or majority, whichever is higher\n  text: You must be at least the age at which your country lets you consent to the processing of your own personal\n    data, or the age of majority there if that is higher.\n"
source_yaml_url: https://artifacts.apis.io/robottraining-jobs/eligibility/robottraining-jobs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from RobotTraining.jobs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Job Board
- Robotics
- Employment
- Artificial Intelligence
---
