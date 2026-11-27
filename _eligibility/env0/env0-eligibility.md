---
api_specs:
- filename: env0-agents-api-openapi.yml
  format: yaml
  label: Env0 Agents API
  slug: env0-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-agents-api-openapi.yml
- filename: env0-configuration-api-openapi.yml
  format: yaml
  label: Env0 Configuration API
  slug: env0-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-configuration-api-openapi.yml
- filename: env0-deployments-api-openapi.yml
  format: yaml
  label: Env0 Deployments API
  slug: env0-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-deployments-api-openapi.yml
- filename: env0-environments-api-openapi.yml
  format: yaml
  label: Env0 Environments API
  slug: env0-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-environments-api-openapi.yml
- filename: env0-modules-api-openapi.yml
  format: yaml
  label: Env0 Modules API
  slug: env0-modules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-modules-api-openapi.yml
- filename: env0-organizations-api-openapi.yml
  format: yaml
  label: Env0 Organizations API
  slug: env0-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-organizations-api-openapi.yml
- filename: env0-projects-api-openapi.yml
  format: yaml
  label: Env0 Projects API
  slug: env0-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-projects-api-openapi.yml
- filename: env0-templates-api-openapi.yml
  format: yaml
  label: Env0 Templates API
  slug: env0-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-templates-api-openapi.yml
- filename: env0-users-api-openapi.yml
  format: yaml
  label: Env0 Users API
  slug: env0-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-users-api-openapi.yml
- filename: env0-webhooks-api-openapi.yml
  format: yaml
  label: Env0 Webhooks API
  slug: env0-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-webhooks-api-openapi.yml
- filename: env0-approval-policies-api-openapi.yml
  format: yaml
  label: Env0 Approval Policies API
  slug: env0-approval-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-approval-policies-api-openapi.yml
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
  - summary: Internal business purposes only
    text: You may use the App and/or Site for internal business purposes only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: env zero reserves the right to refuse to allow you to open an account for any reason in its sole discretion and/or to change the method of logging in.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Env0
provenance_date: '2026-11-09'
provider_name: Env0
provider_slug: env0
slug: env0-eligibility
source_date: '2026-11-09'
source_filename: env0-eligibility.yml
source_heading: Eligibility
source_page: https://www.envzero.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Env0\naid: env0\nurl: https://www.envzero.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Internal business purposes only\n  text: You may use the App and/or Site for internal business purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: env zero reserves the right to refuse to allow you to open an account for any reason in its sole discretion\n    and/or to change the method of logging in.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/env0/eligibility/env0-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Env0's own page on 2026-11-09.
synthetic: false
tags:
- FinOps
- Infrastructure as Code
- DevOps
- Cloud
- Terraform
- OpenTofu
- Platform Engineering
- Cloud Governance
- Drift Detection
- A2A
---
