---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Face recognition and biometric uses
    text: Ximilar’s platform is not designed for and must not be used for face recognition, biometric identification, biometric categorisation, or emotion inference.
  - summary: High-risk AI uses
    text: the user is solely responsible for determining whether their intended use is a “high-risk AI system” under Annex III of the EU AI Act
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
name: Ximilar
provenance_date: '2026-11-10'
provider_name: Ximilar
provider_slug: ximilar
slug: ximilar-eligibility
source_date: '2026-11-10'
source_filename: ximilar-eligibility.yml
source_heading: Eligibility
source_page: https://www.ximilar.com/terms-of-use-privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ximilar\naid: ximilar\nurl: https://www.ximilar.com/terms-of-use-privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Face recognition and biometric uses\n  text: Ximilar’s platform is not designed for and must not be used for face recognition, biometric identification,\n    biometric categorisation, or emotion inference.\n- summary: High-risk AI uses\n  text: the user is solely responsible for determining whether their intended use is a “high-risk AI system” under\n    Annex III of the EU AI Act\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ximilar/eligibility/ximilar-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Ximilar's own page on 2026-11-10.
synthetic: false
tags:
- Computer Vision
- Image Recognition
- Visual Search
- Image Tagging
- Machine Learning
- Artificial Intelligence
- OCR
- Collectibles
- Fashion
- E-Commerce
- MCP
- Image Processing
---
