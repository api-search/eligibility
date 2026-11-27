---
api_specs:
- filename: nationalize-nationality-api-openapi.yml
  format: yaml
  label: Nationalize.io Nationality API
  slug: nationalize-nationality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nationalize/openapi/nationalize-nationality-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer habitually resident in the European Union, you retain the benefit of any mandatory consumer protection provisions of your country of residence.
    type: individual
  - text: You may use the Services for any lawful commercial or non-commercial purpose
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful discrimination
    text: Do not use predictions to unlawfully discriminate against individuals on the basis of gender, age, nationality, or ethnicity.
  - summary: Legal, medical, financial, employment decisions
    text: They should not be used as the sole basis for legal, medical, financial, or employment decisions, or for any purpose that could result in material harm to individuals.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access paid features, you must create an account with a valid email address and password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nationalize.io
provenance_date: '2026-11-10'
provider_name: Nationalize.io
provider_slug: nationalize
slug: nationalize-eligibility
source_date: '2026-11-10'
source_filename: nationalize-eligibility.yml
source_heading: Eligibility
source_page: https://nationalize.io/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nationalize.io\naid: nationalize\nurl: https://nationalize.io/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer habitually resident in the European Union, you retain the benefit of any mandatory\n    consumer protection provisions of your country of residence.\n- type: business\n  text: You may use the Services for any lawful commercial or non-commercial purpose\nrestricted_uses:\n- summary: Unlawful discrimination\n  text: Do not use predictions to unlawfully discriminate against individuals\
  \ on the basis of gender, age, nationality,\n    or ethnicity.\n- summary: Legal, medical, financial, employment decisions\n  text: They should not be used as the sole basis for legal, medical, financial, or employment decisions, or for\n    any purpose that could result in material harm to individuals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access paid features, you must create an account with a valid email address and password.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nationalize/eligibility/nationalize-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Nationalize.io's own page on 2026-11-10.
synthetic: false
tags:
- Nationality
- Name Prediction
- Demographics
- Probabilistic Models
- People
---
