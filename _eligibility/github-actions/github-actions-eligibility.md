---
api_specs:
- filename: github-actions-oidc-api-openapi.yml
  format: yaml
  label: GitHub Actions OIDC API
  slug: github-actions-oidc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-actions/openapi/github-actions-oidc-api-openapi.yml
- filename: github-actions-actions-api-openapi.yml
  format: yaml
  label: GitHub Actions Actions API
  slug: github-actions-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-actions/openapi/github-actions-actions-api-openapi.yml
- filename: github-actions-merge-queue-api-openapi.yml
  format: yaml
  label: GitHub Actions Merge Queue API
  slug: github-actions-merge-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-actions/openapi/github-actions-merge-queue-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: GitHub may allow persons in certain sanctioned countries or territories to access certain GitHub services pursuant to U.S. government authorizations.
  entity_types:
  - text: You must be a human to create an Account.
    type: individual
  - text: If you are a government User or otherwise accessing or using any GitHub Service in a government capacity, this Government Amendment to GitHub Terms of Service applies to you
    type: government
  minimum_age:
    text: You must be age 13 or older.
    value: '13'
  restricted_uses:
  - summary: Export control and sanctions
    text: You may not use GitHub in violation of export control or sanctions laws of the United States or any other applicable jurisdiction.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GitHub Actions
provenance_date: '2026-11-09'
provider_name: GitHub Actions
provider_slug: github-actions
slug: github-actions-eligibility
source_date: '2026-11-09'
source_filename: github-actions-eligibility.yml
source_heading: Eligibility
source_page: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GitHub Actions\naid: github-actions\nurl: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: GitHub may allow persons in certain sanctioned countries or territories to access certain GitHub services\n    pursuant to U.S. government authorizations.\nentity_types:\n- type: individual\n  text: You must be a human to create an Account.\n- type: government\n  text: If you are a government User or otherwise accessing or using any GitHub Service in a government capacity,\n    this Government Amendment to GitHub Terms\
  \ of Service applies to you\nrestricted_uses:\n- summary: Export control and sanctions\n  text: You may not use GitHub in violation of export control or sanctions laws of the United States or any other\n    applicable jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address in order to complete the signup process.\nminimum_age:\n  value: '13'\n  text: You must be age 13 or older.\n"
source_yaml_url: https://artifacts.apis.io/github-actions/eligibility/github-actions-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from GitHub Actions's own page on 2026-11-09.
synthetic: false
tags:
- CI/CD
- Continuous Integration
- Continuous Deployment
- DevOps
- Pipelines
- Workflows
- Automation
- Developer Tools
- Software Development
- Build Automation
- T1
- GitHub
---
