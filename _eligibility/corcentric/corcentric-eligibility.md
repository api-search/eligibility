---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CN
    - RU
    served: []
    text: if you (or any Subscribing Entity you represent) reside or are located or based in China, Russia, or any other jurisdiction to which we apply Conditional Access Measures
  minimum_age:
    text: NO PART OF THE SITE IS INTENDED FOR PERSONS UNDER THE AGE OF 18.
    value: '18'
  restricted_uses:
  - summary: Impersonation or unauthorized access
    text: Create a false identity or impersonate another person or entity in any way
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CN
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Corcentric
provenance_date: '2026-11-09'
provider_name: Corcentric
provider_slug: corcentric
slug: corcentric-eligibility
source_date: '2026-11-09'
source_filename: corcentric-eligibility.yml
source_heading: Eligibility
source_page: https://www.corcentric.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corcentric\naid: corcentric\nurl: https://www.corcentric.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CN\n  - RU\n  text: if you (or any Subscribing Entity you represent) reside or are located or based in China, Russia, or any\n    other jurisdiction to which we apply Conditional Access Measures\nentity_types: []\nrestricted_uses:\n- summary: Impersonation or unauthorized access\n  text: Create a false identity or impersonate another person or entity in any way\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: NO PART OF THE SITE IS INTENDED FOR PERSONS UNDER THE AGE OF 18.\n"
source_yaml_url: https://artifacts.apis.io/corcentric/eligibility/corcentric-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Corcentric's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- B2B
- Cloud
- Fleet Management
- Receivables
---
