---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - MX
    text: Glorify currently offers hardware sales and deposit pre-orders only for eligible delivery addresses in the United States, Canada excluding the Province of Québec, and Mexico.
  minimum_age:
    text: The Services are not intended for children, and Glorify may set age, consent, or account requirements for particular features or regions.
    value: null
  restricted_uses:
  - summary: Not for medical, emergency or professional use
    text: Do not use the Services for diagnosis, treatment, monitoring, prevention, emergency response, crisis support, safety-critical decisions, or other professional purposes.
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
name: Glorify
provenance_date: '2026-11-09'
provider_name: Glorify
provider_slug: glorify
slug: glorify-eligibility
source_date: '2026-11-09'
source_filename: glorify-eligibility.yml
source_heading: Eligibility
source_page: https://www.glorify.global/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glorify\naid: glorify\nurl: https://www.glorify.global/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - MX\n  excluded: []\n  text: Glorify currently offers hardware sales and deposit pre-orders only for eligible delivery addresses in the\n    United States, Canada excluding the Province of Québec, and Mexico.\nentity_types: []\nrestricted_uses:\n- summary: Not for medical, emergency or professional use\n  text: Do not use the Services for diagnosis, treatment, monitoring, prevention, emergency response, crisis support,\n    safety-critical decisions, or other professional\
  \ purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The Services are not intended for children, and Glorify may set age, consent, or account requirements for\n    particular features or regions.\n"
source_yaml_url: https://artifacts.apis.io/glorify/eligibility/glorify-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Glorify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Religion
- Faith
- Devotional
- Wellness
- Meditation
- Christian
- Consumer App
---
