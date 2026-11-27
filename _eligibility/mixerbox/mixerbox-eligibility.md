---
api_specs:
- filename: mixerbox-gpt-api-openapi.yml
  format: yaml
  label: MixerBox Gpt API
  slug: mixerbox-gpt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixerbox/openapi/mixerbox-gpt-api-openapi.yml
- filename: mixerbox-gpt-plugins-api-openapi.yml
  format: yaml
  label: MixerBox Gpt Plugins API
  slug: mixerbox-gpt-plugins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixerbox/openapi/mixerbox-gpt-plugins-api-openapi.yml
- filename: mixerbox-services-api-openapi.yml
  format: yaml
  label: MixerBox Services API
  slug: mixerbox-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixerbox/openapi/mixerbox-services-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'The MixerBox™ Offerings are not intended for use by: (a) individuals who are unable to enter into legally binding contracts under applicable law; and/or (b) individuals under thirteen (13) years of age'
    type: individual
  minimum_age:
    text: individuals under thirteen (13) years of age (or the applicable age of majority, if greater than thirteen (13) years of age)
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: Unless otherwise expressly authorized by MixerBox™ in writing in each instance, End-Users may only use the MixerBox™ Offerings for their own personal, non-commercial use.
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
name: MixerBox
provenance_date: '2026-11-10'
provider_name: MixerBox
provider_slug: mixerbox
slug: mixerbox-eligibility
source_date: '2026-11-10'
source_filename: mixerbox-eligibility.yml
source_heading: Eligibility
source_page: https://www.mbplayer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MixerBox\naid: mixerbox\nurl: https://www.mbplayer.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'The MixerBox™ Offerings are not intended for use by: (a) individuals who are unable to enter into legally\n    binding contracts under applicable law; and/or (b) individuals under thirteen (13) years of age'\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: Unless otherwise expressly authorized by MixerBox™ in writing in each instance, End-Users may only use the\n    MixerBox™ Offerings for their own personal,\
  \ non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: individuals under thirteen (13) years of age (or the applicable age of majority, if greater than thirteen\n    (13) years of age)\n"
source_yaml_url: https://artifacts.apis.io/mixerbox/eligibility/mixerbox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from MixerBox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Artificial Intelligence
- ChatGPT Plugins
- GPT Actions
- Music
- Weather
- Translation
- Productivity
---
