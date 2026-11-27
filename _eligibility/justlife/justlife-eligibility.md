---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    - SA
    text: United Arab Emirates Dubai Abu Dhabi Sharjah Ajman Saudi Arabia Jeddah Riyadh
  minimum_age:
    text: Customers using the website who are minors/under the age of 18 shall not register as a user of the website and shall not transact on or use the website.
    value: '18'
  restricted_uses:
  - summary: No trading with OFAC/sanctioned countries
    text: Justlife will not trade with or provide any services to OFAC and sanctioned countries.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Justlife checks the backgrounds of service professionals/3rd party service providers both directly and indirectly via third-party background check services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Justlife
provenance_date: '2026-11-09'
provider_name: Justlife
provider_slug: justlife
slug: justlife-eligibility
source_date: '2026-11-09'
source_filename: justlife-eligibility.yml
source_heading: Eligibility
source_page: https://www.justlife.com/en-AE/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Justlife\naid: justlife\nurl: https://www.justlife.com/en-AE/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AE\n  - SA\n  excluded: []\n  text: United Arab Emirates Dubai Abu Dhabi Sharjah Ajman Saudi Arabia Jeddah Riyadh\nentity_types: []\nrestricted_uses:\n- summary: No trading with OFAC/sanctioned countries\n  text: Justlife will not trade with or provide any services to OFAC and sanctioned countries.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Justlife checks the backgrounds of service professionals/3rd party service providers both directly and indirectly\n \
  \   via third-party background check services.\nminimum_age:\n  value: '18'\n  text: Customers using the website who are minors/under the age of 18 shall not register as a user of the website\n    and shall not transact on or use the website.\n"
source_yaml_url: https://artifacts.apis.io/justlife/eligibility/justlife-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Justlife's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Home Services
- Marketplace
- Cleaning
- Beauty and Wellness
- Healthcare
- Consumer App
- Middle East
---
