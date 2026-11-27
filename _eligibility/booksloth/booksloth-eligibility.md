---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are of legal age to form a binding contract, or you are over the age of 13 and will use the User Account under the supervision of a parent or guardian
    type: individual
  minimum_age:
    text: The Booked platform, Services, and Apps are not intended for, or targeted to, anyone under the age of 13
    value: '13'
  restricted_uses:
  - summary: No illegal activity
    text: Your registration and your use of the Booked Website and/or any Booked App is not prohibited by law, and will not be used to engage in, commit, or facilitate any illegal activity.
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
name: Booksloth
provenance_date: '2026-11-09'
provider_name: Booksloth
provider_slug: booksloth
slug: booksloth-eligibility
source_date: '2026-11-09'
source_filename: booksloth-eligibility.yml
source_heading: Eligibility
source_page: https://www.booksloth.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Booksloth\naid: booksloth\nurl: https://www.booksloth.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are of legal age to form a binding contract, or you are over the age of 13 and will use the User Account\n    under the supervision of a parent or guardian\nrestricted_uses:\n- summary: No illegal activity\n  text: Your registration and your use of the Booked Website and/or any Booked App is not prohibited by law, and\n    will not be used to engage in, commit, or facilitate any illegal activity.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Booked platform, Services, and Apps are not intended for, or targeted to, anyone under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/booksloth/eligibility/booksloth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Booksloth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Book
- Community
- Reading
- App
---
