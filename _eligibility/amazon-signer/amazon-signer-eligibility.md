---
api_specs:
- filename: amazon-signer-signing-jobs-api-openapi.yml
  format: yaml
  label: Amazon Signer Signing Jobs API
  slug: amazon-signer-signing-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-signer/openapi/amazon-signer-signing-jobs-api-openapi.yml
- filename: amazon-signer-signing-platforms-api-openapi.yml
  format: yaml
  label: Amazon Signer Signing Platforms API
  slug: amazon-signer-signing-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-signer/openapi/amazon-signer-signing-platforms-api-openapi.yml
- filename: amazon-signer-signing-profiles-api-openapi.yml
  format: yaml
  label: Amazon Signer Signing Profiles API
  slug: amazon-signer-signing-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-signer/openapi/amazon-signer-signing-profiles-api-openapi.yml
- filename: amazon-signer-tags-api-openapi.yml
  format: yaml
  label: Amazon Signer Tags API
  slug: amazon-signer-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-signer/openapi/amazon-signer-tags-api-openapi.yml
- filename: amazon-signer-revocations-api-openapi.yml
  format: yaml
  label: Amazon Signer Revocations API
  slug: amazon-signer-revocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-signer/openapi/amazon-signer-revocations-api-openapi.yml
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
  - summary: Microsoft Software High Risk Use
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical equipment, motor vehicles, weaponry systems, or any similar scenario
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
name: Amazon Signer
provenance_date: '2026-11-09'
provider_name: Amazon Signer
provider_slug: amazon-signer
slug: amazon-signer-eligibility
source_date: '2026-11-09'
source_filename: amazon-signer-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Signer\naid: amazon-signer\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Microsoft Software High Risk Use\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other\n    modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical\n    equipment, motor vehicles, weaponry systems, or any similar scenario\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-signer/eligibility/amazon-signer-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amazon Signer's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Code Signing
- IoT
- Lambda
- Security
---
