---
api_specs:
- filename: placid-openai-api-openapi.yml
  format: yaml
  label: Placid Openai API
  slug: placid-openai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placid/openapi/placid-openai-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a natural person or an authorized representative of a legal entity (like a company), and you must be legally able to form a binding contract.
    type: individual
  - text: You must be a natural person or an authorized representative of a legal entity (like a company)
    type: business
  minimum_age:
    text: Otherwise you need to be directly supervised by a parent or guardian who agrees to these terms.
    value: null
  restricted_uses:
  - summary: Prohibited purposes
    text: Gambling/betting, terrorism, creation of „fake news“, military use, generation of training data for the development or research of artificial intelligence.
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
name: Placid
provenance_date: '2026-11-10'
provider_name: Placid
provider_slug: placid
slug: placid-eligibility
source_date: '2026-11-10'
source_filename: placid-eligibility.yml
source_heading: Eligibility
source_page: https://placid.app/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Placid\naid: placid\nurl: https://placid.app/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a natural person or an authorized representative of a legal entity (like a company), and you\n    must be legally able to form a binding contract.\n- type: business\n  text: You must be a natural person or an authorized representative of a legal entity (like a company)\nrestricted_uses:\n- summary: Prohibited purposes\n  text: Gambling/betting, terrorism, creation of „fake news“, military use, generation of\
  \ training data for the\n    development or research of artificial intelligence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Otherwise you need to be directly supervised by a parent or guardian who agrees to these terms.\n"
source_yaml_url: https://artifacts.apis.io/placid/eligibility/placid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Placid's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Creative
- Image Generation
- No-Code
---
