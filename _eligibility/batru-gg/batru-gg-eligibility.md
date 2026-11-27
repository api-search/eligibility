---
api_specs:
- filename: batru-gg-openapi-generated.yml
  format: yaml
  label: Batru API
  slug: batru-gg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/batru-gg/openapi/_ae-authored/batru-gg-openapi-generated.yml
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
  - summary: No betting or wagering use
    text: we do not endorse or facilitate sports betting or wagering of any kind.
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
name: Batru
provenance_date: '2026-11-09'
provider_name: Batru
provider_slug: batru-gg
slug: batru-gg-eligibility
source_date: '2026-11-09'
source_filename: batru-gg-eligibility.yml
source_heading: Eligibility
source_page: https://batru.gg/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Batru\naid: batru-gg\nurl: https://batru.gg/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No betting or wagering use\n  text: we do not endorse or facilitate sports betting or wagering of any kind.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/batru-gg/eligibility/batru-gg-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Batru's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Esports
- Analytics
- Artificial Intelligence
- Competitive
---
