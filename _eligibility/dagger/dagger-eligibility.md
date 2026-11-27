---
api_specs:
- filename: dagger-graph-ql-api-openapi.yml
  format: yaml
  label: Dagger Graph QL API
  slug: dagger-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dagger/openapi/dagger-graph-ql-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users must be over the age of 18, and, if a business, duly organized and legally in good standing.
    type: individual
  - text: A Customer must take all reasonable steps to ensure that its Users comply with these Terms.
    type: business
  minimum_age:
    text: Users must be over the age of 18
    value: '18'
  restricted_uses:
  - summary: Illegal, harmful or offensive use
    text: You shall not use, or encourage, promote, facilitate or instruct others to use the Services for any illegal, harmful or offensive use
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
name: Dagger
provenance_date: '2026-11-09'
provider_name: Dagger
provider_slug: dagger
slug: dagger-eligibility
source_date: '2026-11-09'
source_filename: dagger-eligibility.yml
source_heading: Eligibility
source_page: https://dagger.io/legal_pages/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dagger\naid: dagger\nurl: https://dagger.io/legal_pages/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users must be over the age of 18, and, if a business, duly organized and legally in good standing.\n- type: business\n  text: A Customer must take all reasonable steps to ensure that its Users comply with these Terms.\nrestricted_uses:\n- summary: Illegal, harmful or offensive use\n  text: You shall not use, or encourage, promote, facilitate or instruct others to use the Services for any illegal,\n    harmful or\
  \ offensive use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must be over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/dagger/eligibility/dagger-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dagger's own page on 2026-11-09.
synthetic: false
tags:
- Build Automation
- BuildKit
- CI/CD
- Containers
- DAG
- Daggerverse
- DevOps
- GraphQL
- Modules
- OCI
- Open Source
- Pipelines
- Programmable Pipelines
- SDK
---
