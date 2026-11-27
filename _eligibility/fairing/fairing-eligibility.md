---
api_specs:
- filename: fairing-questions-api-openapi.yml
  format: yaml
  label: Fairing Questions API
  slug: fairing-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairing/openapi/fairing-questions-api-openapi.yml
- filename: fairing-responses-api-openapi.yml
  format: yaml
  label: Fairing Responses API
  slug: fairing-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairing/openapi/fairing-responses-api-openapi.yml
- filename: fairing-sources-api-openapi.yml
  format: yaml
  label: Fairing Sources API
  slug: fairing-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairing/openapi/fairing-sources-api-openapi.yml
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
  - summary: No third-party service bureau use
    text: may not make available or use the Services for the benefit of any third party, including, but not limited to, as a service bureau
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
name: Fairing
provenance_date: '2026-11-09'
provider_name: Fairing
provider_slug: fairing
slug: fairing-eligibility
source_date: '2026-11-09'
source_filename: fairing-eligibility.yml
source_heading: Eligibility
source_page: https://fairing.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fairing\naid: fairing\nurl: https://fairing.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No third-party service bureau use\n  text: may not make available or use the Services for the benefit of any third party, including, but not limited\n    to, as a service bureau\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fairing/eligibility/fairing-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Fairing's own page on 2026-11-09.
synthetic: false
tags:
- Post-Purchase
- Surveys
- Marketing
- Attribution
- E-Commerce
---
