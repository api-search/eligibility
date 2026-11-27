---
api_specs:
- filename: hashicorp-auth-api-openapi.yml
  format: yaml
  label: HashiCorp Auth API
  slug: hashicorp-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hashicorp/openapi/hashicorp-auth-api-openapi.yml
- filename: hashicorp-identity-api-openapi.yml
  format: yaml
  label: HashiCorp Identity API
  slug: hashicorp-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hashicorp/openapi/hashicorp-identity-api-openapi.yml
- filename: hashicorp-secrets-api-openapi.yml
  format: yaml
  label: HashiCorp Secrets API
  slug: hashicorp-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hashicorp/openapi/hashicorp-secrets-api-openapi.yml
- filename: hashicorp-system-api-openapi.yml
  format: yaml
  label: HashiCorp System API
  slug: hashicorp-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hashicorp/openapi/hashicorp-system-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We are making the Website available to you for your information and personal use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes or unauthorized content
    text: 'You may not: use our Website for any illegal purpose;'
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
name: HashiCorp
provenance_date: '2026-11-09'
provider_name: HashiCorp
provider_slug: hashicorp
slug: hashicorp-eligibility
source_date: '2026-11-09'
source_filename: hashicorp-eligibility.yml
source_heading: Eligibility
source_page: https://www.hashicorp.com/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HashiCorp\naid: hashicorp\nurl: https://www.hashicorp.com/en/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We are making the Website available to you for your information and personal use only.\nrestricted_uses:\n- summary: Illegal purposes or unauthorized content\n  text: 'You may not: use our Website for any illegal purpose;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hashicorp/eligibility/hashicorp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from HashiCorp's own page on 2026-11-09.
synthetic: false
tags:
- Cloud
- DevOps
- Infrastructure
- Platform
---
