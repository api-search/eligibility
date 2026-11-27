---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is available only for individuals aged 13 years or older or the digital age of consent in your country, if older.
    type: individual
  - text: If you use AppMaster on behalf of your business, you are representing that you are authorized to agree to these Term on its behalf.
    type: business
  minimum_age:
    text: The Service is available only for individuals aged 13 years or older or the digital age of consent in your country, if older.
    value: '13'
  restricted_uses:
  - summary: E-Commerce activities require age 18+
    text: In order to conduct E-Commerce Activities, you must be 18 years or older or at least the age of majority in your country of residence
  - summary: Regional discount plan limits
    text: Plans that include regional discounts are strictly limited to applications with no more than 5 end-users, no more than 500 monthly visits
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may, in our sole discretion, refuse to offer the Service to any person or entity and change the eligibility criteria for using the Service at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AppMaster.io
provenance_date: '2026-11-09'
provider_name: AppMaster.io
provider_slug: appmaster
slug: appmaster-eligibility
source_date: '2026-11-09'
source_filename: appmaster-eligibility.yml
source_heading: Eligibility
source_page: https://appmaster.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppMaster.io\naid: appmaster\nurl: https://appmaster.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is available only for individuals aged 13 years or older or the digital age of consent in your\n    country, if older.\n- type: business\n  text: If you use AppMaster on behalf of your business, you are representing that you are authorized to agree to\n    these Term on its behalf.\nrestricted_uses:\n- summary: E-Commerce activities require age 18+\n  text: In order to conduct E-Commerce\
  \ Activities, you must be 18 years or older or at least the age of majority\n    in your country of residence\n- summary: Regional discount plan limits\n  text: Plans that include regional discounts are strictly limited to applications with no more than 5 end-users,\n    no more than 500 monthly visits\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may, in our sole discretion, refuse to offer the Service to any person or entity and change the eligibility\n    criteria for using the Service at any time.\nminimum_age:\n  value: '13'\n  text: The Service is available only for individuals aged 13 years or older or the digital age of consent in your\n    country, if older.\n"
source_yaml_url: https://artifacts.apis.io/appmaster/eligibility/appmaster-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AppMaster.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- No-Code
- Platform
- Automation
- Integration
---
