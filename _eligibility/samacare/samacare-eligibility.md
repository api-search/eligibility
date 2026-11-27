---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: SamaCare makes no representation that the SamaCare Service is appropriate, may be downloaded, or is available for use outside the USA. Access to the SamaCare Service where the content or access or use of the SamaCare Service is illegal is prohibited.
  entity_types:
  - text: If you are eligible to be a SamaCare member, and desire to obtain a license to access and use our SamaCare Service
    type: business
  minimum_age:
    text: You represent and warrant that you are at least 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: Illegal access or use prohibited
    text: Access to the SamaCare Service where the content or access or use of the SamaCare Service is illegal is prohibited.
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
name: SamaCare
provenance_date: '2026-11-10'
provider_name: SamaCare
provider_slug: samacare
slug: samacare-eligibility
source_date: '2026-11-10'
source_filename: samacare-eligibility.yml
source_heading: Eligibility
source_page: https://samacare.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SamaCare\naid: samacare\nurl: https://samacare.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: SamaCare makes no representation that the SamaCare Service is appropriate, may be downloaded, or is available\n    for use outside the USA. Access to the SamaCare Service where the content or access or use of the SamaCare Service\n    is illegal is prohibited.\nentity_types:\n- type: business\n  text: If you are eligible to be a SamaCare member, and desire to obtain a license to access and use our SamaCare\n    Service\nrestricted_uses:\n- summary: Illegal access or\
  \ use prohibited\n  text: Access to the SamaCare Service where the content or access or use of the SamaCare Service is illegal is\n    prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent and warrant that you are at least 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/samacare/eligibility/samacare-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SamaCare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Prior Authorization
- Patient Access
- Specialty Pharmacy
- Life Sciences
- Electronic Health Records
- Revenue Cycle Management
- Market Access
- Artificial Intelligence
---
