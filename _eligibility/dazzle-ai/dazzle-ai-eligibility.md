---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age (or the legal age of majority in your jurisdiction) to access or use the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the legal age of majority in your jurisdiction) to access or use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Upload, share, or transmit any content that is unlawful, defamatory, harassing, hateful, obscene, infringing on third-party intellectual property, or promoting harm against any group or individual.
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
name: Dazzle AI
provenance_date: '2026-11-09'
provider_name: Dazzle AI
provider_slug: dazzle-ai
slug: dazzle-ai-eligibility
source_date: '2026-11-09'
source_filename: dazzle-ai-eligibility.yml
source_heading: Eligibility
source_page: https://dazzle.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dazzle AI\naid: dazzle-ai\nurl: https://dazzle.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age (or the legal age of majority in your jurisdiction) to access or use\n    the Services.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Upload, share, or transmit any content that is unlawful, defamatory, harassing, hateful, obscene, infringing\n    on third-party intellectual property, or promoting harm against any group or individual.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the legal age of majority in your jurisdiction) to access or use\n    the Services.\n"
source_yaml_url: https://artifacts.apis.io/dazzle-ai/eligibility/dazzle-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Dazzle AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Consumer
- Pre-Launch
---
