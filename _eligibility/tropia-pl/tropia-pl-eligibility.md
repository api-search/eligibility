---
api_specs:
- filename: tropia-pl-openapi.yml
  format: yaml
  label: tropia.pl API
  slug: tropia-pl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tropia-pl/openapi/tropia-pl-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Konsument oraz przedsiębiorca na prawach konsumenta ma 14 dni na odstąpienie od umowy.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: tropia-pl
provenance_date: '2026-11-10'
provider_name: tropia-pl
provider_slug: tropia-pl
slug: tropia-pl-eligibility
source_date: '2026-11-10'
source_filename: tropia-pl-eligibility.yml
source_heading: Eligibility
source_page: https://tropia.pl/regulamin
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tropia-pl\naid: tropia-pl\nurl: https://tropia.pl/regulamin\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Konsument oraz przedsiębiorca na prawach konsumenta ma 14 dni na odstąpienie od umowy.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tropia-pl/eligibility/tropia-pl-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from tropia-pl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Poland
- Finance
- Public Records
---
