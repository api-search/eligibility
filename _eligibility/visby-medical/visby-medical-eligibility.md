---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Service for use only by persons located in the United States.
  minimum_age:
    text: you represent that you are at least the age of majority in your jurisdiction of residence
    value: age of majority
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: use our products for any illegal, unlawful, or unauthorized purpose
  - summary: Commercial purpose or financial gain
    text: use the Services for any commercial purpose or financial gain
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
name: Visby Medical
provenance_date: '2026-11-10'
provider_name: Visby Medical
provider_slug: visby-medical
slug: visby-medical-eligibility
source_date: '2026-11-10'
source_filename: visby-medical-eligibility.yml
source_heading: Eligibility
source_page: https://visby.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Visby Medical\naid: visby-medical\nurl: https://visby.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Service for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: use our products for any illegal, unlawful, or unauthorized purpose\n- summary: Commercial purpose or financial gain\n  text: use the Services for any commercial purpose or financial gain\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: age of majority\n  text: you represent that you are at least the age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/visby-medical/eligibility/visby-medical-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Visby Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Biology
- Diagnostics
- Molecular Diagnostics
- PCR
- Point of Care
- Healthcare
- Sexual Health
- Medical Devices
- Telehealth
- At-Home Testing
- FDA-Approved
---
