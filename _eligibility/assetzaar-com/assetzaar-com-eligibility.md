---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to use Assetzaar.
    value: '16'
  restricted_uses:
  - summary: Unlawful purposes or IP infringement
    text: You may not use the service for unlawful purposes, to infringe intellectual property, or to upload malware or harmful content.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: approved sellers list and sell their own
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Assetzaar
provenance_date: '2026-11-09'
provider_name: Assetzaar
provider_slug: assetzaar-com
slug: assetzaar-com-eligibility
source_date: '2026-11-09'
source_filename: assetzaar-com-eligibility.yml
source_heading: Eligibility
source_page: https://assetzaar.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Assetzaar\naid: assetzaar-com\nurl: https://assetzaar.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes or IP infringement\n  text: You may not use the service for unlawful purposes, to infringe intellectual property, or to upload malware\n    or harmful content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: approved sellers list and sell their own\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use Assetzaar.\n"
source_yaml_url: https://artifacts.apis.io/assetzaar-com/eligibility/assetzaar-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Assetzaar's own page on 2026-11-09.
synthetic: false
tags:
- Marketplace
- React
- Next.js
- Software-as-a-Service
- Components
- Artificial Intelligence
- Templates
---
