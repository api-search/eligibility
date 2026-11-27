---
api_specs:
- filename: circleci-runner-api-openapi.yml
  format: yaml
  label: CircleCI Self-Hosted Runner API
  slug: runner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-runner-api-openapi.yml
- filename: circleci-webhooks-asyncapi.yml
  format: yaml
  label: CircleCI Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/circleci/asyncapi/circleci-webhooks-asyncapi.yml
- filename: circleci-artifact-api-openapi.yml
  format: yaml
  label: CircleCI Artifact API
  slug: circleci-artifact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-artifact-api-openapi.yml
- filename: circleci-build-api-openapi.yml
  format: yaml
  label: CircleCI Build API
  slug: circleci-build-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-build-api-openapi.yml
- filename: circleci-context-api-openapi.yml
  format: yaml
  label: CircleCI Context API
  slug: circleci-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-context-api-openapi.yml
- filename: circleci-insights-api-openapi.yml
  format: yaml
  label: CircleCI Insights API
  slug: circleci-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-insights-api-openapi.yml
- filename: circleci-job-api-openapi.yml
  format: yaml
  label: CircleCI Job API
  slug: circleci-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-job-api-openapi.yml
- filename: circleci-pipeline-api-openapi.yml
  format: yaml
  label: CircleCI Pipeline API
  slug: circleci-pipeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-pipeline-api-openapi.yml
- filename: circleci-project-api-openapi.yml
  format: yaml
  label: CircleCI Project API
  slug: circleci-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-project-api-openapi.yml
- filename: circleci-resource-class-api-openapi.yml
  format: yaml
  label: CircleCI Resource Class API
  slug: circleci-resource-class-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-resource-class-api-openapi.yml
- filename: circleci-runner-task-api-openapi.yml
  format: yaml
  label: CircleCI Runner Task API
  slug: circleci-runner-task-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-runner-task-api-openapi.yml
- filename: circleci-schedule-api-openapi.yml
  format: yaml
  label: CircleCI Schedule API
  slug: circleci-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-schedule-api-openapi.yml
- filename: circleci-ssh-key-api-openapi.yml
  format: yaml
  label: CircleCI SSH Key API
  slug: circleci-ssh-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-ssh-key-api-openapi.yml
- filename: circleci-test-metadata-api-openapi.yml
  format: yaml
  label: CircleCI Test Metadata API
  slug: circleci-test-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-test-metadata-api-openapi.yml
- filename: circleci-user-api-openapi.yml
  format: yaml
  label: CircleCI User API
  slug: circleci-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-user-api-openapi.yml
- filename: circleci-webhook-api-openapi.yml
  format: yaml
  label: CircleCI Webhook API
  slug: circleci-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-webhook-api-openapi.yml
- filename: circleci-workflow-api-openapi.yml
  format: yaml
  label: CircleCI Workflow API
  slug: circleci-workflow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circleci/openapi/circleci-workflow-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: To avoid access interruption or denial, you and your Users should not log into CircleCI Services while in a country or territory sanctioned by the U.S. government.
  entity_types:
  - text: your employer/entity you represent, its Affiliates and Users, or, if that does not apply, you as an individual
    type: business
  - text: or, if that does not apply, you as an individual
    type: individual
  - text: If your employer/entity is a U.S. Government Agency or this Agreement becomes subject to the Federal Acquisition Regulations
    type: government
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Export-controlled data
    text: You will not submit any data controlled under the U.S. International Traffic in Arms Regulations.
  - summary: Restricted parties and embargoed territories
    text: You represent and warrant that you and your Users are not listed on any U.S. government list of prohibited or restricted parties or located in (or a national of) a country or territory subject to a U.S. government embargo
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
name: CircleCI
provenance_date: '2026-11-09'
provider_name: CircleCI
provider_slug: circleci
slug: circleci-eligibility
source_date: '2026-11-09'
source_filename: circleci-eligibility.yml
source_heading: Eligibility
source_page: https://circleci.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CircleCI\naid: circleci\nurl: https://circleci.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: To avoid access interruption or denial, you and your Users should not log into CircleCI Services while in\n    a country or territory sanctioned by the U.S. government.\nentity_types:\n- type: business\n  text: your employer/entity you represent, its Affiliates and Users, or, if that does not apply, you as an individual\n- type: individual\n  text: or, if that does not apply, you as an individual\n- type: government\n  text: If your employer/entity is a U.S.\
  \ Government Agency or this Agreement becomes subject to the Federal Acquisition\n    Regulations\nrestricted_uses:\n- summary: Export-controlled data\n  text: You will not submit any data controlled under the U.S. International Traffic in Arms Regulations.\n- summary: Restricted parties and embargoed territories\n  text: You represent and warrant that you and your Users are not listed on any U.S. government list of prohibited\n    or restricted parties or located in (or a national of) a country or territory subject to a U.S. government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/circleci/eligibility/circleci-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from CircleCI's own page on 2026-11-09.
synthetic: false
tags:
- CI/CD
- Continuous Integration
- Continuous Deployment
- DevOps
- Pipelines
- Workflows
- Developer Tools
---
