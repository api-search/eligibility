---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a minor i.e. under the age of 18 years, you cannot not register as a Client or a Candidate or transact on or use the Website.
    type: individual
  - text: you may avail our Services by registering as a client (Client)
    type: business
  minimum_age:
    text: If you are a minor i.e. under the age of 18 years, you cannot not register as a Client or a Candidate or transact on or use the Website.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Once you complete the registration, we will create an account for you and you may login to your account using your username and password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Entropik
provenance_date: '2026-11-09'
provider_name: Entropik
provider_slug: entropik
slug: entropik-eligibility
source_date: '2026-11-09'
source_filename: entropik-eligibility.yml
source_heading: Eligibility
source_page: https://www.askdecode.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Entropik\naid: entropik\nurl: https://www.askdecode.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a minor i.e. under the age of 18 years, you cannot not register as a Client or a Candidate or\n    transact on or use the Website.\n- type: business\n  text: you may avail our Services by registering as a client (Client)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Once you complete the registration, we will create an account for you and you may login to\
  \ your account\n    using your username and password.\nminimum_age:\n  value: '18'\n  text: If you are a minor i.e. under the age of 18 years, you cannot not register as a Client or a Candidate or\n    transact on or use the Website.\n"
source_yaml_url: https://artifacts.apis.io/entropik/eligibility/entropik-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Entropik's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Emotion AI
- Consumer Insights
- User Research
- Market Research
- Insights Platform
- Eye Tracking
- Software-as-a-Service
---
