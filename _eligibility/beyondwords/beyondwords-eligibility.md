---
api_specs:
- filename: beyondwords-openapi-generated.yml
  format: yaml
  label: BeyondWords API
  slug: beyondwords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyondwords/openapi/_ae-authored/beyondwords-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual, you represent that you are at least 18 years of age
    type: individual
  - text: you are entering the Agreement on behalf of an entity
    type: business
  minimum_age:
    text: if you are an individual, you represent that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No unlawful or harmful material
    text: 'This includes accessing, storing, distributing or transmitting viruses or any material during you use our Services that: is unlawful, harmful, threatening, defamatory, obscene, infringing, harassing'
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
name: BeyondWords
provenance_date: '2026-11-09'
provider_name: BeyondWords
provider_slug: beyondwords
slug: beyondwords-eligibility
source_date: '2026-11-09'
source_filename: beyondwords-eligibility.yml
source_heading: Eligibility
source_page: https://beyondwords.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeyondWords\naid: beyondwords\nurl: https://beyondwords.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual, you represent that you are at least 18 years of age\n- type: business\n  text: you are entering the Agreement on behalf of an entity\nrestricted_uses:\n- summary: No unlawful or harmful material\n  text: 'This includes accessing, storing, distributing or transmitting viruses or any material during you use our\n    Services that: is unlawful, harmful, threatening, defamatory, obscene, infringing,\
  \ harassing'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are an individual, you represent that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/beyondwords/eligibility/beyondwords-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BeyondWords's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Audio
- CMS
- Publishing
- Voice Cloning
---
