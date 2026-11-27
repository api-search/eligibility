---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The user confirms and guarantees that he/she is at least thirteen (13) years of age, and if he/she is under 13, he/she cannot, under any circumstance, use the platform.
    value: '13'
  restricted_uses:
  - summary: Cryptocurrency promotion
    text: Using the platform to promote content related to cryptocurrencies and similar financial instruments.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: The Developer is not obligated to verify the identity of the Users
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beamer
provenance_date: '2026-11-09'
provider_name: Beamer
provider_slug: beamer
slug: beamer-eligibility
source_date: '2026-11-09'
source_filename: beamer-eligibility.yml
source_heading: Eligibility
source_page: https://www.getbeamer.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beamer\naid: beamer\nurl: https://www.getbeamer.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Cryptocurrency promotion\n  text: Using the platform to promote content related to cryptocurrencies and similar financial instruments.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: The Developer is not obligated to verify the identity of the Users\nminimum_age:\n  value: '13'\n  text: The user confirms and guarantees that he/she is at least thirteen (13) years of age, and if he/she\
  \ is under\n    13, he/she cannot, under any circumstance, use the platform.\n"
source_yaml_url: https://artifacts.apis.io/beamer/eligibility/beamer-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Beamer's own page on 2026-11-09.
synthetic: false
tags:
- Changelog
- Deprecation
- Notification
- Product Updates
- User Engagement
- Webhook
- NPS
- Feedback
---
