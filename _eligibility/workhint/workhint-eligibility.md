---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old, have authority to enter into these Terms, and comply with all applicable laws.
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or harmful use
    text: You may not use Workhint to violate laws, run fraudulent operations, exploit workers unlawfully, or distribute harmful content.
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
name: Workhint
provenance_date: '2026-11-10'
provider_name: Workhint
provider_slug: workhint
slug: workhint-eligibility
source_date: '2026-11-10'
source_filename: workhint-eligibility.yml
source_heading: Eligibility
source_page: https://workhint.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workhint\naid: workhint\nurl: https://workhint.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, fraudulent or harmful use\n  text: You may not use Workhint to violate laws, run fraudulent operations, exploit workers unlawfully, or distribute\n    harmful content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, have authority to enter into these Terms, and comply with all applicable\n   \
  \ laws.\n"
source_yaml_url: https://artifacts.apis.io/workhint/eligibility/workhint-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Workhint's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Workforce Management
- Work Orchestration
- Staffing
- Payments
- Compliance
- Artificial Intelligence
- Software-as-a-Service
---
