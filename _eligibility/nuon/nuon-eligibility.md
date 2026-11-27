---
api_specs:
- filename: nuon-accounts-api-openapi.yml
  format: yaml
  label: Nuon Accounts API
  slug: nuon-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-accounts-api-openapi.yml
- filename: nuon-actions-api-openapi.yml
  format: yaml
  label: Nuon Actions API
  slug: nuon-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-actions-api-openapi.yml
- filename: nuon-actions-runner-api-openapi.yml
  format: yaml
  label: Nuon Actions/runner API
  slug: nuon-actions-runner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-actions-runner-api-openapi.yml
- filename: nuon-apps-api-openapi.yml
  format: yaml
  label: Nuon Apps API
  slug: nuon-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-apps-api-openapi.yml
- filename: nuon-auth-api-openapi.yml
  format: yaml
  label: Nuon Auth API
  slug: nuon-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-auth-api-openapi.yml
- filename: nuon-components-api-openapi.yml
  format: yaml
  label: Nuon Components API
  slug: nuon-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-components-api-openapi.yml
- filename: nuon-general-api-openapi.yml
  format: yaml
  label: Nuon General API
  slug: nuon-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-general-api-openapi.yml
- filename: nuon-installs-api-openapi.yml
  format: yaml
  label: Nuon Installs API
  slug: nuon-installs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-installs-api-openapi.yml
- filename: nuon-notebooks-api-openapi.yml
  format: yaml
  label: Nuon Notebooks API
  slug: nuon-notebooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-notebooks-api-openapi.yml
- filename: nuon-onboarding-api-openapi.yml
  format: yaml
  label: Nuon Onboarding API
  slug: nuon-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-onboarding-api-openapi.yml
- filename: nuon-orgs-api-openapi.yml
  format: yaml
  label: Nuon Orgs API
  slug: nuon-orgs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-orgs-api-openapi.yml
- filename: nuon-policy-reports-api-openapi.yml
  format: yaml
  label: Nuon Policy Reports API
  slug: nuon-policy-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-policy-reports-api-openapi.yml
- filename: nuon-queues-api-openapi.yml
  format: yaml
  label: Nuon Queues API
  slug: nuon-queues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-queues-api-openapi.yml
- filename: nuon-runbooks-api-openapi.yml
  format: yaml
  label: Nuon Runbooks API
  slug: nuon-runbooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-runbooks-api-openapi.yml
- filename: nuon-runners-api-openapi.yml
  format: yaml
  label: Nuon Runners API
  slug: nuon-runners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-runners-api-openapi.yml
- filename: nuon-runners-runner-api-openapi.yml
  format: yaml
  label: Nuon Runners/runner API
  slug: nuon-runners-runner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-runners-runner-api-openapi.yml
- filename: nuon-slack-api-openapi.yml
  format: yaml
  label: Nuon Slack API
  slug: nuon-slack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-slack-api-openapi.yml
- filename: nuon-vcs-api-openapi.yml
  format: yaml
  label: Nuon VCS API
  slug: nuon-vcs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuon/openapi/nuon-vcs-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Nuon makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: you are (i) at least eighteen (18) years old
    type: individual
  - text: THE AUTHORITY TO ENTER INTO THE AGREEMENT PERSONALLY OR ON BEHALF OF THE LEGAL ENTITY IDENTIFIED DURING THE ACCOUNT REGISTRATION PROCESS
    type: business
  minimum_age:
    text: (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Export control
    text: You may not use, export, import, or transfer any Services except as authorized by U.S. law, the laws of the jurisdiction in which you obtained the Services, and any other applicable laws.
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
name: Nuon
provenance_date: '2026-11-10'
provider_name: Nuon
provider_slug: nuon
slug: nuon-eligibility
source_date: '2026-11-10'
source_filename: nuon-eligibility.yml
source_heading: Eligibility
source_page: https://nuon.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nuon\naid: nuon\nurl: https://nuon.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Nuon makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: you are (i) at least eighteen (18) years old\n- type: business\n  text: THE AUTHORITY TO ENTER INTO THE AGREEMENT PERSONALLY OR ON BEHALF OF THE LEGAL ENTITY IDENTIFIED DURING\n    THE ACCOUNT REGISTRATION PROCESS\nrestricted_uses:\n- summary: Export control\n  text: You may not use, export, import, or transfer any Services except as authorized\
  \ by U.S. law, the laws of\n    the jurisdiction in which you obtained the Services, and any other applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/nuon/eligibility/nuon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nuon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- BYOC
- Deployment
- Continuous Delivery
- DevOps
- Infrastructure
- Cloud
- Multi-Cloud
- Kubernetes
- Terraform
- Platform Engineering
---
