---
api_specs:
- filename: vigil-wtf-vigil-proxy-api-openapi.yml
  format: yaml
  label: Vigil Proxy
  slug: vigil-wtf-vigil-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigil-wtf/openapi/vigil-wtf-vigil-proxy-api-openapi.yml
- filename: vigil-wtf-feedback-api-openapi.yml
  format: yaml
  label: Vigil Feedback API
  slug: vigil-wtf-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigil-wtf/openapi/vigil-wtf-feedback-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16, and if you are using Vigil for an organisation you must be authorised to accept these terms on its behalf.
    type: individual
  - text: if you are using Vigil for an organisation you must be authorised to accept these terms on its behalf.
    type: business
  minimum_age:
    text: You must be at least 16
    value: '16'
  restricted_uses:
  - summary: Unlawful use
    text: Break the law, or help anyone else break it.
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
name: Vigil
provenance_date: '2026-11-10'
provider_name: Vigil
provider_slug: vigil-wtf
slug: vigil-wtf-eligibility
source_date: '2026-11-10'
source_filename: vigil-wtf-eligibility.yml
source_heading: Eligibility
source_page: https://www.vigil.tools/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vigil\naid: vigil-wtf\nurl: https://www.vigil.tools/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16, and if you are using Vigil for an organisation you must be authorised to accept\n    these terms on its behalf.\n- type: business\n  text: if you are using Vigil for an organisation you must be authorised to accept these terms on its behalf.\nrestricted_uses:\n- summary: Unlawful use\n  text: Break the law, or help anyone else break it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16\n"
source_yaml_url: https://artifacts.apis.io/vigil-wtf/eligibility/vigil-wtf-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vigil's own page on 2026-11-10.
synthetic: false
tags:
- Monitoring
- AI Middleware
- Security
- Analytics
---
