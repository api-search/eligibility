---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Service may be unavailable depending on geographic location.
  minimum_age:
    text: Depending on your country of residence, if you are below 18 years old and you choose to use the Service, we may ask consent from your parent or legal guardian.
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: Company provides the App and the Service to Users only for personal, non-commercial and entertainment purposes
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
name: VCNC
provenance_date: '2026-11-10'
provider_name: VCNC
provider_slug: vcnc
slug: vcnc-eligibility
source_date: '2026-11-10'
source_filename: vcnc-eligibility.yml
source_heading: Eligibility
source_page: https://between.us/policy/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VCNC\naid: vcnc\nurl: https://between.us/policy/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Service may be unavailable depending on geographic location.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use\n  text: Company provides the App and the Service to Users only for personal, non-commercial and entertainment purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Depending on your country of residence, if you are below 18 years old and you choose to use the Service,\n    we may ask\
  \ consent from your parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/vcnc/eligibility/vcnc-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from VCNC's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobility
- Ride Hailing
- Messaging
- Social
- Consumer App
- South Korea
---
