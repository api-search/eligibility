---
api_specs:
- filename: zenml-artifacts-api-openapi.yml
  format: yaml
  label: ZenML Artifacts API
  slug: zenml-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-artifacts-api-openapi.yml
- filename: zenml-auth-api-openapi.yml
  format: yaml
  label: ZenML Auth API
  slug: zenml-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-auth-api-openapi.yml
- filename: zenml-deployments-api-openapi.yml
  format: yaml
  label: ZenML Deployments API
  slug: zenml-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-deployments-api-openapi.yml
- filename: zenml-models-api-openapi.yml
  format: yaml
  label: ZenML Models API
  slug: zenml-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-models-api-openapi.yml
- filename: zenml-pipeline-runs-api-openapi.yml
  format: yaml
  label: ZenML Pipeline Runs API
  slug: zenml-pipeline-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-pipeline-runs-api-openapi.yml
- filename: zenml-pipelines-api-openapi.yml
  format: yaml
  label: ZenML Pipelines API
  slug: zenml-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-pipelines-api-openapi.yml
- filename: zenml-projects-api-openapi.yml
  format: yaml
  label: ZenML Projects API
  slug: zenml-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-projects-api-openapi.yml
- filename: zenml-schedules-api-openapi.yml
  format: yaml
  label: ZenML Schedules API
  slug: zenml-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-schedules-api-openapi.yml
- filename: zenml-secrets-api-openapi.yml
  format: yaml
  label: ZenML Secrets API
  slug: zenml-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-secrets-api-openapi.yml
- filename: zenml-service-connectors-api-openapi.yml
  format: yaml
  label: ZenML Service Connectors API
  slug: zenml-service-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-service-connectors-api-openapi.yml
- filename: zenml-stack-components-api-openapi.yml
  format: yaml
  label: ZenML Stack Components API
  slug: zenml-stack-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-stack-components-api-openapi.yml
- filename: zenml-stacks-api-openapi.yml
  format: yaml
  label: ZenML Stacks API
  slug: zenml-stacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-stacks-api-openapi.yml
- filename: zenml-users-api-openapi.yml
  format: yaml
  label: ZenML Users API
  slug: zenml-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenml/openapi/zenml-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered only to businesses within the meaning of Section 14 of the German Civil Code (BGB)
    type: business
  - text: and to public-law entities
    type: government
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Protected health information
    text: The Services are not, by default, set up for protected health information under the US Health Insurance Portability and Accountability Act (HIPAA) or similar rules, or for classified information.
  - summary: Sole basis for significant automated decisions
    text: use the output of the Services as the sole basis for a decision with legal or similarly significant effects on an individual without meaningful human review
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
name: ZenML
provenance_date: '2026-11-10'
provider_name: ZenML
provider_slug: zenml
slug: zenml-eligibility
source_date: '2026-11-10'
source_filename: zenml-eligibility.yml
source_heading: Eligibility
source_page: https://www.zenml.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZenML\naid: zenml\nurl: https://www.zenml.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are offered only to businesses within the meaning of Section 14 of the German Civil Code (BGB)\n- type: government\n  text: and to public-law entities\nrestricted_uses:\n- summary: Protected health information\n  text: The Services are not, by default, set up for protected health information under the US Health Insurance\n    Portability and Accountability Act (HIPAA) or similar rules, or for classified information.\n\
  - summary: Sole basis for significant automated decisions\n  text: use the output of the Services as the sole basis for a decision with legal or similarly significant effects\n    on an individual without meaningful human review\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/zenml/eligibility/zenml-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ZenML's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- MLOps
- LLMOps
- Pipelines
- Open Source
- Python
---
