---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Be 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: Shared logins
    text: Shared logins across multiple users are not allowed.
  - summary: Unlawful use
    text: Use your account only for lawful purposes.
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
name: Kimola
provenance_date: '2026-11-09'
provider_name: Kimola
provider_slug: kimola
slug: kimola-eligibility
source_date: '2026-11-09'
source_filename: kimola-eligibility.yml
source_heading: Eligibility
source_page: https://kimola.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kimola\naid: kimola\nurl: https://kimola.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Shared logins\n  text: Shared logins across multiple users are not allowed.\n- summary: Unlawful use\n  text: Use your account only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Be 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/kimola/eligibility/kimola-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Kimola's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Market Research
- Customer Feedback
- Text Analytics
- Sentiment Analysis
- Natural Language Processing
- Consumer Insights
- Machine Learning
- Artificial Intelligence
---
