---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We control and operate our Service from the United States and we make no representations or warranties that the information or services provided through our Service are appropriate for access or use in other jurisdictions.
  entity_types:
  - text: You must be 18 years or older in order to sign up for a subscription to the service
    type: individual
  minimum_age:
    text: You must be 18 years or older in order to sign up for a subscription to the service
    value: '18'
  restricted_uses:
  - summary: Monitoring own minor children only
    text: You may register only your own minor child or children to be monitored under your subscription to the Service.
  - summary: English language interactions only
    text: The Service currently supports English language interactions only.
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
name: Kidas
provenance_date: '2026-11-09'
provider_name: Kidas
provider_slug: kidas
slug: kidas-eligibility
source_date: '2026-11-09'
source_filename: kidas-eligibility.yml
source_heading: Eligibility
source_page: https://getkidas.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kidas\naid: kidas\nurl: https://getkidas.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We control and operate our Service from the United States and we make no representations or warranties that\n    the information or services provided through our Service are appropriate for access or use in other jurisdictions.\nentity_types:\n- type: individual\n  text: You must be 18 years or older in order to sign up for a subscription to the service\nrestricted_uses:\n- summary: Monitoring own minor children only\n  text: You may register only your own minor child or\
  \ children to be monitored under your subscription to the Service.\n- summary: English language interactions only\n  text: The Service currently supports English language interactions only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older in order to sign up for a subscription to the service\n"
source_yaml_url: https://artifacts.apis.io/kidas/eligibility/kidas-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Kidas's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trust and Safety
- Scam Detection
- Fraud Prevention
- Cybersecurity
- Gaming
- Deepfake Protection
- Discord
---
