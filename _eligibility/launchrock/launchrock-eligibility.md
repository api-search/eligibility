---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are offered and controlled from facilities in the United States; those accessing from other jurisdictions are responsible for local law compliance.
  entity_types:
  - text: The Services are offered and available only to users who are 18 years of age or older, and are fully able and competent to enter into the terms
    type: individual
  minimum_age:
    text: are not under the age of 18
    value: '18'
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
name: LaunchRock
provenance_date: '2026-11-09'
provider_name: LaunchRock
provider_slug: launchrock
slug: launchrock-eligibility
source_date: '2026-11-09'
source_filename: launchrock-eligibility.yml
source_heading: Eligibility
source_page: https://www.launchrock.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LaunchRock\naid: launchrock\nurl: https://www.launchrock.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are offered and controlled from facilities in the United States; those accessing from other\n    jurisdictions are responsible for local law compliance.\nentity_types:\n- type: individual\n  text: The Services are offered and available only to users who are 18 years of age or older, and are fully able\n    and competent to enter into the terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: are not under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/launchrock/eligibility/launchrock-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from LaunchRock's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Landing Pages
- Website Builder
- No-Code
- Customer Acquisition
- Email Capture
- Waitlist
- Product Launch
- Startups
- Marketing
---
