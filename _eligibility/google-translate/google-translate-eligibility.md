---
api_specs:
- filename: google-translate-projects-api-openapi.yml
  format: yaml
  label: Google Cloud Translation API Translate Projects API
  slug: google-translate-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-translate/openapi/google-translate-projects-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or person agreeing to these terms
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: (i) for High Risk Activities; (ii) in violation of the AUP
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must have an Account to use the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Cloud Translation API
provenance_date: '2026-11-09'
provider_name: Google Cloud Translation API
provider_slug: google-translate
slug: google-translate-eligibility
source_date: '2026-11-09'
source_filename: google-translate-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Translation API\naid: google-translate\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the entity or person agreeing to these terms\nrestricted_uses:\n- summary: High-risk activities\n  text: (i) for High Risk Activities; (ii) in violation of the AUP\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must have an Account to use the Services\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-translate/eligibility/google-translate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Google Cloud Translation API's own page on 2026-11-09.
synthetic: false
tags:
- Google Cloud
- Internationalization
- Language Detection
- Localization
- Machine Translation
- Natural Language Processing
- Translation
---
