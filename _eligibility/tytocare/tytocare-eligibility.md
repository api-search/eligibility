---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 16 years please do not visit or use the Site. If you are between 16 and 18 years of age, then you must review these Terms with your parent or guardian
    value: '16'
  restricted_uses:
  - summary: Site not for minors under 16
    text: Out site is not structured to attract children under the age of 16 years. If you are under 16 years please do not visit or use the Site.
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
name: TytoCare
provenance_date: '2026-11-10'
provider_name: TytoCare
provider_slug: tytocare
slug: tytocare-eligibility
source_date: '2026-11-10'
source_filename: tytocare-eligibility.yml
source_heading: Eligibility
source_page: https://www.tytocare.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TytoCare\naid: tytocare\nurl: https://www.tytocare.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Site not for minors under 16\n  text: Out site is not structured to attract children under the age of 16 years. If you are under 16 years please\n    do not visit or use the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: If you are under 16 years please do not visit or use the Site. If you are between 16 and 18 years of age,\n\
  \    then you must review these Terms with your parent or guardian\n"
source_yaml_url: https://artifacts.apis.io/tytocare/eligibility/tytocare-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from TytoCare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Remote Patient Monitoring
- Medical Devices
- Virtual Care
- Artificial Intelligence
---
