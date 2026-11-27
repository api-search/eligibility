---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Agreement is applicable to all persons who use or access the Platform and/or the Services, whether in their individual capacity or on behalf of any third party
    type: individual
  - text: If the User is agreeing to these terms on behalf of a business or an individual other than User, User represents and warrants that User has authority to bind that business
    type: business
  minimum_age:
    text: Our services are not intended for or directed to children under the age of 18.
    value: '18'
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
name: Complement 1
provenance_date: '2026-11-09'
provider_name: Complement 1
provider_slug: complement-1
slug: complement-1-eligibility
source_date: '2026-11-09'
source_filename: complement-1-eligibility.yml
source_heading: Eligibility
source_page: https://www.complement1.com/tnc.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Complement 1\naid: complement-1\nurl: https://www.complement1.com/tnc.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Agreement is applicable to all persons who use or access the Platform and/or the Services, whether\n    in their individual capacity or on behalf of any third party\n- type: business\n  text: If the User is agreeing to these terms on behalf of a business or an individual other than User, User represents\n    and warrants that User has authority to bind that business\nrestricted_uses: []\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our services are not intended for or directed to children under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/complement-1/eligibility/complement-1-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Complement 1's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Oncology
- Lifestyle
- Digital Health
---
