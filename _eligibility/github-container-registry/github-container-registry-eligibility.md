---
api_specs:
- filename: github-container-registry-merge-queue-api-openapi.yml
  format: yaml
  label: GitHub Container Registry Merge Queue API
  slug: github-container-registry-merge-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-container-registry/openapi/github-container-registry-merge-queue-api-openapi.yml
- filename: github-container-registry-packages-api-openapi.yml
  format: yaml
  label: GitHub Container Registry Packages API
  slug: github-container-registry-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-container-registry/openapi/github-container-registry-packages-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: GitHub may allow persons in certain sanctioned countries or territories to access certain GitHub services pursuant to U.S. government authorizations.
  entity_types:
  - text: A User must be at least 13 years of age.
    type: individual
  - text: Special terms may apply for business or government Accounts
    type: business
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
    text: You must be a human to create an Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GitHub Container Registry
provenance_date: '2026-11-09'
provider_name: GitHub Container Registry
provider_slug: github-container-registry
slug: github-container-registry-eligibility
source_date: '2026-11-09'
source_filename: github-container-registry-eligibility.yml
source_heading: Eligibility
source_page: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GitHub Container Registry\naid: github-container-registry\nurl: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: GitHub may allow persons in certain sanctioned countries or territories to access certain GitHub services\n    pursuant to U.S. government authorizations.\nentity_types:\n- type: individual\n  text: A User must be at least 13 years of age.\n- type: business\n  text: Special terms may apply for business or government Accounts\nrestricted_uses:\n- summary: Export control and sanctions\n  text: You\
  \ may not use GitHub in violation of export control or sanctions laws of the United States or any other\n    applicable jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must be a human to create an Account.\nminimum_age:\n  value: '13'\n  text: You must be age 13 or older.\n"
source_yaml_url: https://artifacts.apis.io/github-container-registry/eligibility/github-container-registry-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from GitHub Container Registry's own page on 2026-11-09.
synthetic: false
tags:
- Container Images
- Containers
- GitHub
- Packages
- Registry
- OCI
- Docker
---
