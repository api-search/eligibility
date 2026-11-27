---
api_specs:
- filename: jenkins-computer-api-openapi.yml
  format: yaml
  label: Jenkins Computer API
  slug: jenkins-computer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jenkins/openapi/jenkins-computer-api-openapi.yml
- filename: jenkins-jobs-api-openapi.yml
  format: yaml
  label: Jenkins Jobs API
  slug: jenkins-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jenkins/openapi/jenkins-jobs-api-openapi.yml
- filename: jenkins-queue-api-openapi.yml
  format: yaml
  label: Jenkins Queue API
  slug: jenkins-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jenkins/openapi/jenkins-queue-api-openapi.yml
- filename: jenkins-server-api-openapi.yml
  format: yaml
  label: Jenkins Server API
  slug: jenkins-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jenkins/openapi/jenkins-server-api-openapi.yml
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
  - summary: Harassment and endangerment
    text: Harassment. Violating explicitly expressed boundaries or engaging in unnecessary personal attention after any clear request to stop.
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
name: Jenkins
provenance_date: '2026-11-09'
provider_name: Jenkins
provider_slug: jenkins
slug: jenkins-eligibility
source_date: '2026-11-09'
source_filename: jenkins-eligibility.yml
source_heading: Eligibility
source_page: https://www.jenkins.io/project/conduct/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jenkins\naid: jenkins\nurl: https://www.jenkins.io/project/conduct/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment and endangerment\n  text: Harassment. Violating explicitly expressed boundaries or engaging in unnecessary personal attention after\n    any clear request to stop.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jenkins/eligibility/jenkins-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Jenkins's own page on 2026-11-09.
synthetic: false
tags:
- Automation
- Build Server
- CI/CD
- Continuous Delivery
- Continuous Integration
- DevOps
- Open Source
- Remote Access API
---
