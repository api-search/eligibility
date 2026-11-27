---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Client refers to the legal entity which concludes the Agreement with Presti.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Deepfakes and illegal content
    text: Generate misleading or fraudulent content, including deepfakes impersonating individuals without consent
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
name: Presti
provenance_date: '2026-11-10'
provider_name: Presti
provider_slug: presti
slug: presti-eligibility
source_date: '2026-11-10'
source_filename: presti-eligibility.yml
source_heading: Eligibility
source_page: https://www.presti.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Presti\naid: presti\nurl: https://www.presti.ai/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Client refers to the legal entity which concludes the Agreement with Presti.\nrestricted_uses:\n- summary: Deepfakes and illegal content\n  text: Generate misleading or fraudulent content, including deepfakes impersonating individuals without consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/presti/eligibility/presti-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Presti's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Applicative Saas
- Artificial Intelligence
- Generative AI
- E-Commerce
- Product Photography
- Image Generation
- Video Generation
- Retail
---
