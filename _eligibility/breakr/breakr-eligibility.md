---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to create an account and use the Platform’s core services
    value: '18'
  restricted_uses:
  - summary: No circumvention of platform payments
    text: All Users agree not to circumvent the Platform’s payment system.
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
name: Breakr
provenance_date: '2026-11-09'
provider_name: Breakr
provider_slug: breakr
slug: breakr-eligibility
source_date: '2026-11-09'
source_filename: breakr-eligibility.yml
source_heading: Eligibility
source_page: https://www.breakr.app/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Breakr\naid: breakr\nurl: https://www.breakr.app/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No circumvention of platform payments\n  text: All Users agree not to circumvent the Platform’s payment system.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to create an account\n    and use the Platform’s core services\n"
source_yaml_url: https://artifacts.apis.io/breakr/eligibility/breakr-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Breakr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Creator Economy
- Fintech
- Software-as-a-Service
- Payments
---
