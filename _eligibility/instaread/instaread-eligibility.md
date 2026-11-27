---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: When you create an account with us, you guarantee that you are 18 years of age or older
    type: individual
  minimum_age:
    text: you guarantee that you are 18 years of age or older
    value: '18'
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
name: Instaread
provenance_date: '2026-11-09'
provider_name: Instaread
provider_slug: instaread
slug: instaread-eligibility
source_date: '2026-11-09'
source_filename: instaread-eligibility.yml
source_heading: Eligibility
source_page: https://instaread.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Instaread\naid: instaread\nurl: https://instaread.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: When you create an account with us, you guarantee that you are 18 years of age or older\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you guarantee that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/instaread/eligibility/instaread-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Instaread's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Audio
- Text-to-Speech
- Publishing
- Media
- Accessibility
- Book Summaries
- WordPress
---
