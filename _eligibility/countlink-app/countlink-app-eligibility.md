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
  - summary: Unlawful, harassing, or deceptive use
    text: 'You agree not to use the Service to: violate any applicable law; harass, defraud, or deceive others'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Service does not require an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CountLink
provenance_date: '2026-11-09'
provider_name: CountLink
provider_slug: countlink-app
slug: countlink-app-eligibility
source_date: '2026-11-09'
source_filename: countlink-app-eligibility.yml
source_heading: Eligibility
source_page: https://countlink.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CountLink\naid: countlink-app\nurl: https://countlink.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, harassing, or deceptive use\n  text: 'You agree not to use the Service to: violate any applicable law; harass, defraud, or deceive others'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Service does not require an account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/countlink-app/eligibility/countlink-app-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from CountLink's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Countdown Timer
- Shared Timer
- Productivity
- Education
- Meetings
- Model Context Protocol
- Web App
---
