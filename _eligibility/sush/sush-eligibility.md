---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old or the legal age of majority in your jurisdiction.
    type: individual
  minimum_age:
    text: Be at least 18 years old or the legal age of majority in your jurisdiction.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Provide accurate, current, and complete information during the registration process and keep your account information updated.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sush.io
provenance_date: '2026-11-10'
provider_name: Sush.io
provider_slug: sush
slug: sush-eligibility
source_date: '2026-11-10'
source_filename: sush-eligibility.yml
source_heading: Eligibility
source_page: https://sush.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sush.io\naid: sush\nurl: https://sush.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old or the legal age of majority in your jurisdiction.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Provide accurate, current, and complete information during the registration process and keep your account\n    information updated.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old or the legal age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/sush/eligibility/sush-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Sush.io's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Accounting
- Integration
- Software-as-a-Service
- Automation
- Payments
---
