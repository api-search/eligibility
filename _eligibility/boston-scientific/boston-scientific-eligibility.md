---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site is intended for use by U.S. residents only and contains information regarding BSC products and services available for sale or distribution within the U.S..
  entity_types:
  - text: Certain areas of this Site contain information intended only for medical professionals. Accordingly, BSC reserves the right to limit access to certain areas of the Site to medical professionals who register and meet the qualifications imposed by us.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You may not access, download, use or export the Site or the Content in violation of U.S. export laws or regulations
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Upon our review and acceptance of your registration information, BSC will provide you with a User ID and password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Boston Scientific
provenance_date: '2026-11-09'
provider_name: Boston Scientific
provider_slug: boston-scientific
slug: boston-scientific-eligibility
source_date: '2026-11-09'
source_filename: boston-scientific-eligibility.yml
source_heading: Eligibility
source_page: https://www.bostonscientific.com/en-US/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boston Scientific\naid: boston-scientific\nurl: https://www.bostonscientific.com/en-US/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site is intended for use by U.S. residents only and contains information regarding BSC products and\n    services available for sale or distribution within the U.S..\nentity_types:\n- type: individual\n  text: Certain areas of this Site contain information intended only for medical professionals. Accordingly, BSC\n    reserves the right to limit access to certain areas of the Site to medical professionals who register and\
  \ meet\n    the qualifications imposed by us.\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not access, download, use or export the Site or the Content in violation of U.S. export laws or\n    regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Upon our review and acceptance of your registration information, BSC will provide you with a User ID and\n    password.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boston-scientific/eligibility/boston-scientific-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Boston Scientific's own page on 2026-11-09.
synthetic: false
tags:
- Medical Devices
- Digital Health
- Cardiology
- Urology
- Endoscopy
- Neuromodulation
- Fortune 500
---
