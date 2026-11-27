---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old (or the minimum age of digital consent where you live) to use the Service.
    value: '16'
  restricted_uses:
  - summary: Sexual content involving minors
    text: Sexual content involving minors, or any content that exploits or endangers children — this is never permitted and will be reported where required.
  - summary: Deceptive or fraudulent content
    text: Deceptive or fraudulent content — including impersonation, disinformation, or misleading "deepfakes" of real people.
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
name: Bloopo
provenance_date: '2026-11-09'
provider_name: Bloopo
provider_slug: bloopo-ai
slug: bloopo-ai-eligibility
source_date: '2026-11-09'
source_filename: bloopo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bloopo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloopo\naid: bloopo-ai\nurl: https://bloopo.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sexual content involving minors\n  text: Sexual content involving minors, or any content that exploits or endangers children — this is never permitted\n    and will be reported where required.\n- summary: Deceptive or fraudulent content\n  text: Deceptive or fraudulent content — including impersonation, disinformation, or misleading \"deepfakes\" of\n    real people.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old (or the minimum age of digital consent where you live) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bloopo-ai/eligibility/bloopo-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bloopo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Creative
- Collaboration
- Marketing
- Image Generation
- Company
---
