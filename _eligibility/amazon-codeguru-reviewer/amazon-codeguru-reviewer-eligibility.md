---
api_specs:
- filename: amazon-codeguru-reviewer-associations-api-openapi.yml
  format: yaml
  label: Amazon CodeGuru Reviewer Associations API
  slug: amazon-codeguru-reviewer-associations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codeguru-reviewer/openapi/amazon-codeguru-reviewer-associations-api-openapi.yml
- filename: amazon-codeguru-reviewer-codereviews-api-openapi.yml
  format: yaml
  label: Amazon CodeGuru Reviewer Codereviews API
  slug: amazon-codeguru-reviewer-codereviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codeguru-reviewer/openapi/amazon-codeguru-reviewer-codereviews-api-openapi.yml
- filename: amazon-codeguru-reviewer-feedback-api-openapi.yml
  format: yaml
  label: Amazon CodeGuru Reviewer Feedback API
  slug: amazon-codeguru-reviewer-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codeguru-reviewer/openapi/amazon-codeguru-reviewer-feedback-api-openapi.yml
- filename: amazon-codeguru-reviewer-tags-api-openapi.yml
  format: yaml
  label: Amazon CodeGuru Reviewer Tags API
  slug: amazon-codeguru-reviewer-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codeguru-reviewer/openapi/amazon-codeguru-reviewer-tags-api-openapi.yml
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
  - summary: High Risk Use of Microsoft Software
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical equipment, motor vehicles, weaponry systems, or any similar scenario (collectively, “High Risk Use”).
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
name: Amazon CodeGuru Reviewer
provenance_date: '2026-11-09'
provider_name: Amazon CodeGuru Reviewer
provider_slug: amazon-codeguru-reviewer
slug: amazon-codeguru-reviewer-eligibility
source_date: '2026-11-09'
source_filename: amazon-codeguru-reviewer-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon CodeGuru Reviewer\naid: amazon-codeguru-reviewer\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High Risk Use of Microsoft Software\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other\n    modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical\n    equipment, motor vehicles, weaponry systems, or any similar scenario (collectively, “High Risk\
  \ Use”).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-codeguru-reviewer/eligibility/amazon-codeguru-reviewer-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amazon CodeGuru Reviewer's own page on 2026-11-09.
synthetic: false
tags:
- Amazon
- Amazon Web Services
- Code Review
- Security
- DevOps
- Machine Learning
- Developer Tools
---
