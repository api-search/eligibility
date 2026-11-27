---
api_specs:
- filename: jevmodel-app-openapi-generated.yml
  format: yaml
  label: JevModel API
  slug: jevmodel-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jevmodel-app/openapi/_ae-authored/jevmodel-app-openapi-generated.yml
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
  - summary: High-impact decisions
    text: Keep high-impact decisions under appropriate human and deterministic review.
  - summary: Sensitive actions
    text: Do not use a probability alone as authorization to perform a sensitive action.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Playground, Batch, Decision Flows or the API you must register and verify your email.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: JevModel
provenance_date: '2026-11-09'
provider_name: JevModel
provider_slug: jevmodel-app
slug: jevmodel-app-eligibility
source_date: '2026-11-09'
source_filename: jevmodel-app-eligibility.yml
source_heading: Eligibility
source_page: https://jevmodel.app/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JevModel\naid: jevmodel-app\nurl: https://jevmodel.app/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-impact decisions\n  text: Keep high-impact decisions under appropriate human and deterministic review.\n- summary: Sensitive actions\n  text: Do not use a probability alone as authorization to perform a sensitive action.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Playground, Batch, Decision Flows or the API you must register and verify your email.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jevmodel-app/eligibility/jevmodel-app-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from JevModel's own page on 2026-11-09.
synthetic: false
tags:
- Decision API
- Content Moderation
- Spam Filtering
- Support Triage
- Ticket Routing
- Language Detection
- Personal Data Screening
---
