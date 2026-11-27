---
api_specs:
- filename: classifier-dev-account-api-openapi.yml
  format: yaml
  label: classifier-dev Account API
  slug: classifier-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-account-api-openapi.yml
- filename: classifier-dev-classifier-dev-api-openapi.yml
  format: yaml
  label: classifier-dev Classifier.dev API
  slug: classifier-dev-classifier-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-classifier-dev-api-openapi.yml
- filename: classifier-dev-classify-api-openapi.yml
  format: yaml
  label: classifier-dev Classify API
  slug: classifier-dev-classify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-classify-api-openapi.yml
- filename: classifier-dev-docs-api-openapi.yml
  format: yaml
  label: classifier-dev Docs API
  slug: classifier-dev-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-docs-api-openapi.yml
- filename: classifier-dev-feedback-api-openapi.yml
  format: yaml
  label: classifier-dev Feedback API
  slug: classifier-dev-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-feedback-api-openapi.yml
- filename: classifier-dev-subscribe-api-openapi.yml
  format: yaml
  label: classifier-dev Subscribe API
  slug: classifier-dev-subscribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-subscribe-api-openapi.yml
claim_count: 3
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
  - summary: Unlawful classification of people
    text: Do not use it to classify people in ways the law forbids
  - summary: Consequential decisions without human review
    text: to make consequential decisions about a person with no human review
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: with no account and no key
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: classifier-dev
provenance_date: '2026-11-09'
provider_name: classifier-dev
provider_slug: classifier-dev
slug: classifier-dev-eligibility
source_date: '2026-11-09'
source_filename: classifier-dev-eligibility.yml
source_heading: Eligibility
source_page: https://classifier.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: classifier-dev\naid: classifier-dev\nurl: https://classifier.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful classification of people\n  text: Do not use it to classify people in ways the law forbids\n- summary: Consequential decisions without human review\n  text: to make consequential decisions about a person with no human review\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: with no account and no key\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/classifier-dev/eligibility/classifier-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from classifier-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Machine Learning
- Natural Language Processing
- Classification
- OpenAPI
---
