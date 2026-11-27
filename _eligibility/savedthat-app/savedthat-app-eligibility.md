---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use the Service (or older where your local law requires a higher minimum age for consenting to online services).
    value: '13'
  restricted_uses:
  - summary: IOS app device license limit
    text: Your licence to use the app is limited to Apple-branded devices you own or control, as permitted by the App Store Terms of Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: savedthat-app
provenance_date: '2026-11-10'
provider_name: savedthat-app
provider_slug: savedthat-app
slug: savedthat-app-eligibility
source_date: '2026-11-10'
source_filename: savedthat-app-eligibility.yml
source_heading: Eligibility
source_page: https://savedthat.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: savedthat-app\naid: savedthat-app\nurl: https://savedthat.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: IOS app device license limit\n  text: Your licence to use the app is limited to Apple-branded devices you own or control, as permitted by the\n    App Store Terms of Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email to create an account.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service (or older where your\
  \ local law requires a higher minimum\n    age for consenting to online services).\n"
source_yaml_url: https://artifacts.apis.io/savedthat-app/eligibility/savedthat-app-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from savedthat-app's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Artificial Intelligence
- Search
- Transcription
- Productivity
---
