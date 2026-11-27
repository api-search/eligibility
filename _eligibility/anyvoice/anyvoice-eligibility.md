---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Harmful or illegal content
    text: Generate content that is illegal, hateful, sexually exploitative, or that promotes violence.
  - summary: Election or legal interference
    text: Spread misinformation, manipulate elections, or interfere with legal processes.
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
name: Anyvoice
provenance_date: '2026-11-09'
provider_name: Anyvoice
provider_slug: anyvoice
slug: anyvoice-eligibility
source_date: '2026-11-09'
source_filename: anyvoice-eligibility.yml
source_heading: Eligibility
source_page: https://anyvoice.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anyvoice\naid: anyvoice\nurl: https://anyvoice.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harmful or illegal content\n  text: Generate content that is illegal, hateful, sexually exploitative, or that promotes violence.\n- summary: Election or legal interference\n  text: Spread misinformation, manipulate elections, or interfere with legal processes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or\
  \ the age of majority in your jurisdiction, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/anyvoice/eligibility/anyvoice-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Anyvoice's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Voice
- Text-to-Speech
- Speech Synthesis
---
