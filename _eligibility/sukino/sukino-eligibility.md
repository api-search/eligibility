---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: persons including minors, un-discharged insolvents etc. are not eligible to register on, or use/ access the Website.
    value: null
  restricted_uses:
  - summary: No prescription drugs without valid prescription
    text: They must specifically ensure that they are in no way purchasing drugs or pharmaceutical products or services or Prescription Drugs without a valid prescription
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As part of the registration process, Sukino may collect the following personal information from the Users
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sukino
provenance_date: '2026-11-10'
provider_name: Sukino
provider_slug: sukino
slug: sukino-eligibility
source_date: '2026-11-10'
source_filename: sukino-eligibility.yml
source_heading: Eligibility
source_page: https://sukinohealthcare.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sukino\naid: sukino\nurl: https://sukinohealthcare.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No prescription drugs without valid prescription\n  text: They must specifically ensure that they are in no way purchasing drugs or pharmaceutical products or services\n    or Prescription Drugs without a valid prescription\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As part of the registration process, Sukino may collect the following personal information from the Users\nminimum_age:\n\
  \  value: null\n  text: persons including minors, un-discharged insolvents etc. are not eligible to register on, or use/ access\n    the Website.\n"
source_yaml_url: https://artifacts.apis.io/sukino/eligibility/sukino-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Sukino's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Rehabilitation
- Continuum Care
- Home Care
- Elder Care
- Palliative Care
- India
---
