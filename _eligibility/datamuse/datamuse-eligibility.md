---
api_specs:
- filename: datamuse-words-api-openapi.yml
  format: yaml
  label: Datamuse Words API
  slug: datamuse-words-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datamuse/openapi/datamuse-words-api-openapi.yml
- filename: datamuse-pets-api-openapi.yml
  format: yaml
  label: Datamuse Pets API
  slug: datamuse-pets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datamuse/openapi/datamuse-pets-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Datamuse API is a word-finding query engine for developers.
    type: developer
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: starting February 1, 2027 , an API key will be required in all requests
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Datamuse
provenance_date: '2026-11-09'
provider_name: Datamuse
provider_slug: datamuse
slug: datamuse-eligibility
source_date: '2026-11-09'
source_filename: datamuse-eligibility.yml
source_heading: Eligibility
source_page: https://www.datamuse.com/api/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datamuse\naid: datamuse\nurl: https://www.datamuse.com/api/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: The Datamuse API is a word-finding query engine for developers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: starting February 1, 2027 , an API key will be required in all requests\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datamuse/eligibility/datamuse-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Datamuse's own page on 2026-11-09.
synthetic: false
tags:
- Word Finding
- Lexical Search
- Natural-Language
- Vocabulary
- Synonyms
- Antonyms
- Rhymes
- Phonetics
- Semantic Search
- Reverse Dictionary
- Autocomplete
- Wordplay
- Creative Writing
- Vocabulary Apps
- Word Games
- Linguistics
- Open Source Projects
- Public APIs
---
