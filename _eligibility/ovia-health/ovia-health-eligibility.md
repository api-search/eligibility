---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    served: []
    text: you certify you are not accessing any Services or Content (as defined below) from an embargoed destination such as Cuba, Iran, or North Korea. The Services are not intended for use in Quebec.
  minimum_age:
    text: You may not use the Services if you are A) under 13 or if parental consent is required under applicable law for you to use the Services
    value: '13'
  restricted_uses:
  - summary: Harmful or unlawful purpose
    text: otherwise using the Services for a harmful, malicious, disruptive, or unlawful purpose
  - summary: Direct competitors
    text: a direct competitor of Ovia Health investigating the Services for competitive research
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ovia Health
provenance_date: '2026-11-10'
provider_name: Ovia Health
provider_slug: ovia-health
slug: ovia-health-eligibility
source_date: '2026-11-10'
source_filename: ovia-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.oviahealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ovia Health\naid: ovia-health\nurl: https://www.oviahealth.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  text: you certify you are not accessing any Services or Content (as defined below) from an embargoed destination\n    such as Cuba, Iran, or North Korea. The Services are not intended for use in Quebec.\nentity_types: []\nrestricted_uses:\n- summary: Harmful or unlawful purpose\n  text: otherwise using the Services for a harmful, malicious, disruptive, or unlawful purpose\n- summary: Direct competitors\n  text: a direct competitor of Ovia Health\
  \ investigating the Services for competitive research\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may not use the Services if you are A) under 13 or if parental consent is required under applicable\n    law for you to use the Services\n"
source_yaml_url: https://artifacts.apis.io/ovia-health/eligibility/ovia-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ovia Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Women's Health
- Femtech
- Pregnancy
- Fertility
- Employee Benefits
---
