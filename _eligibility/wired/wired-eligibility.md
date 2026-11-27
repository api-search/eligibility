---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation, warranty, covenant or guarantee that the Service or any Products are appropriate, available, or legal in any particular geographic location.
  minimum_age:
    text: The Service is not intended for users under the age of 13
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: Unless otherwise specified, the Service is intended for your personal, non-commercial use only.
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
name: Wired
provenance_date: '2026-11-10'
provider_name: Wired
provider_slug: wired
slug: wired-eligibility
source_date: '2026-11-10'
source_filename: wired-eligibility.yml
source_heading: Eligibility
source_page: https://www.condenast.com/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wired\naid: wired\nurl: https://www.condenast.com/user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation, warranty, covenant or guarantee that the Service or any Products are appropriate,\n    available, or legal in any particular geographic location.\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: Unless otherwise specified, the Service is intended for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '13'\n  text: The Service is not intended for users under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/wired/eligibility/wired-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Wired's own page on 2026-11-10.
synthetic: false
tags:
- Content
- Innovation
- Media
- News
- RSS
- Science
- Technology News
---
