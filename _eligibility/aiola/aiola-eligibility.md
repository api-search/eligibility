---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: individuals who have engaged directly with aiola for their own use
    type: individual
  - text: individuals who have engaged with aiola on behalf of their organization (i.e., their employer or an entity to which they provide services)
    type: business
  minimum_age:
    text: Our Site is available only to individuals who (a) are at least sixteen (16) years old
    value: '16'
  restricted_uses:
  - summary: Illegal or abusive AI Tool use prohibited
    text: Users of the AI Tools are prohibited to use such tools in any illegal, inappropriate and/or abusive manner
  - summary: AI Tools unavailable in some countries
    text: access to the applicable Platform Tool may be restricted in certain countries which are not supported by the AI Tools
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
name: aiOla
provenance_date: '2026-11-09'
provider_name: aiOla
provider_slug: aiola
slug: aiola-eligibility
source_date: '2026-11-09'
source_filename: aiola-eligibility.yml
source_heading: Eligibility
source_page: https://aiola.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: aiOla\naid: aiola\nurl: https://aiola.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: individuals who have engaged directly with aiola for their own use\n- type: business\n  text: individuals who have engaged with aiola on behalf of their organization (i.e., their employer or an entity\n    to which they provide services)\nrestricted_uses:\n- summary: Illegal or abusive AI Tool use prohibited\n  text: Users of the AI Tools are prohibited to use such tools in any illegal, inappropriate and/or abusive manner\n- summary: AI\
  \ Tools unavailable in some countries\n  text: access to the applicable Platform Tool may be restricted in certain countries which are not supported by\n    the AI Tools\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Our Site is available only to individuals who (a) are at least sixteen (16) years old\n"
source_yaml_url: https://artifacts.apis.io/aiola/eligibility/aiola-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from aiOla's own page on 2026-11-09.
synthetic: false
tags:
- Speech Recognition
- Speech-to-Text
- Text-to-Speech
- Voice AI
- Conversational AI
- Artificial Intelligence
- Machine Learning
- Audio
- Transcription
- Enterprise
---
