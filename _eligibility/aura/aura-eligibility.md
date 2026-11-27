---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Full access to plan features depends on identity verification and credit eligibility.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aura
provenance_date: '2026-11-09'
provider_name: Aura
provider_slug: aura
slug: aura-eligibility
source_date: '2026-11-09'
source_filename: aura-eligibility.yml
source_heading: Eligibility
source_page: https://www.aura.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aura\naid: aura\nurl: https://www.aura.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Full access to plan features depends on identity verification and credit eligibility.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aura/eligibility/aura-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Aura's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Digital Safety
- Identity Theft Protection
- Cybersecurity
- Privacy
- Antivirus
- VPN
- Parental Controls
- Fraud Prevention
---
