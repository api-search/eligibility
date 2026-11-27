---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use aNotepad.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use aNotepad. If you are under 18, you must have permission from a parent or legal guardian.
    value: '13'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Upload, share, or distribute illegal, harmful, threatening, abusive, defamatory, or obscene content
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
name: Anotepad
provenance_date: '2026-11-09'
provider_name: Anotepad
provider_slug: anotepad-com
slug: anotepad-com-eligibility
source_date: '2026-11-09'
source_filename: anotepad-com-eligibility.yml
source_heading: Eligibility
source_page: https://anotepad.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anotepad\naid: anotepad-com\nurl: https://anotepad.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use aNotepad.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Upload, share, or distribute illegal, harmful, threatening, abusive, defamatory, or obscene content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use aNotepad. If you are under 18, you must have permission\
  \ from a\n    parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/anotepad-com/eligibility/anotepad-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Anotepad's own page on 2026-11-09.
synthetic: false
tags:
- OnlineNotepad
- Note Taking
- Productivity
- Text Editor
---
