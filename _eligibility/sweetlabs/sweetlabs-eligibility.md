---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU OR THE ENTITY OR COMPANY THAT YOU REPRESENT ("YOU"), acknowledge that you accept the terms
    type: business
  - text: If You are part of an agency, department, or other entity of the United States Government ("Government")
    type: government
  minimum_age:
    text: You may not use the Services, if you are under the age of sixteen (16)
    value: '16'
  restricted_uses:
  - summary: Use restricted to lawful purposes
    text: You agree to use the Services only for the purposes that are permitted by this Agreement and by any applicable law, regulation, or generally accepted practices or guidelines
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To establish an Account, you may be required to provide information about yourself, such as your name, age and email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SweetLabs
provenance_date: '2026-11-10'
provider_name: SweetLabs
provider_slug: sweetlabs
slug: sweetlabs-eligibility
source_date: '2026-11-10'
source_filename: sweetlabs-eligibility.yml
source_heading: Eligibility
source_page: https://files.sweetlabs.com/licenses/20210329/Terms_All.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SweetLabs\naid: sweetlabs\nurl: https://files.sweetlabs.com/licenses/20210329/Terms_All.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: YOU OR THE ENTITY OR COMPANY THAT YOU REPRESENT (\"YOU\"), acknowledge that you accept the terms\n- type: government\n  text: If You are part of an agency, department, or other entity of the United States Government (\"Government\")\nrestricted_uses:\n- summary: Use restricted to lawful purposes\n  text: You agree to use the Services only for the purposes that are permitted by\
  \ this Agreement and by any applicable\n    law, regulation, or generally accepted practices or guidelines\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To establish an Account, you may be required to provide information about yourself, such as your name, age\n    and email address.\nminimum_age:\n  value: '16'\n  text: You may not use the Services, if you are under the age of sixteen (16)\n"
source_yaml_url: https://artifacts.apis.io/sweetlabs/eligibility/sweetlabs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from SweetLabs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Software
- App Distribution
- Device Manufacturers
- Consumer Software
- OEM
---
