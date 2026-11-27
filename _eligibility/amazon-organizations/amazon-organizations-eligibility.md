---
api_specs:
- filename: amazon-organizations-organizations-api-openapi.yml
  format: yaml
  label: Amazon Organizations API
  slug: amazon-organizations-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-organizations-api-openapi.yml
- filename: amazon-organizations-account-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Account API
  slug: amazon-organizations-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-account-api-openapi.yml
- filename: amazon-organizations-aws-service-access-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Aws Service Access API
  slug: amazon-organizations-aws-service-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-aws-service-access-api-openapi.yml
- filename: amazon-organizations-delegated-administrator-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Delegated Administrator API
  slug: amazon-organizations-delegated-administrator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-delegated-administrator-api-openapi.yml
- filename: amazon-organizations-handshake-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Handshake API
  slug: amazon-organizations-handshake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-handshake-api-openapi.yml
- filename: amazon-organizations-operations-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Operations API
  slug: amazon-organizations-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-operations-api-openapi.yml
- filename: amazon-organizations-organizational-unit-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Organizational Unit API
  slug: amazon-organizations-organizational-unit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-organizational-unit-api-openapi.yml
- filename: amazon-organizations-policy-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Policy API
  slug: amazon-organizations-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-policy-api-openapi.yml
- filename: amazon-organizations-resource-policy-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Resource Policy API
  slug: amazon-organizations-resource-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-resource-policy-api-openapi.yml
claim_count: 1
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
  - summary: High-risk use of Microsoft Software
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other modes of human mass transportation, nuclear or chemical facilities, life support systems
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
name: Amazon Organizations
provenance_date: '2026-11-09'
provider_name: Amazon Organizations
provider_slug: amazon-organizations
slug: amazon-organizations-eligibility
source_date: '2026-11-09'
source_filename: amazon-organizations-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Organizations\naid: amazon-organizations\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk use of Microsoft Software\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other\n    modes of human mass transportation, nuclear or chemical facilities, life support systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-organizations/eligibility/amazon-organizations-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amazon Organizations's own page on 2026-11-09.
synthetic: false
tags:
- Account Management
- Amazon Web Services
- Consolidated Billing
- Governance
- Multi-Account
- Organization
- Policies
---
