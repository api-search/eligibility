---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a natural person and, subject to Section 1.2 (Minors) below, an adult of the legal age of majority in your country, province and/or state of residence to use and access the Services
    type: individual
  minimum_age:
    text: In no event will you be able to install, use, or otherwise access the Services (including creating an Account) if you are under the age of thirteen (13).
    value: '13'
  restricted_uses:
  - summary: Sanctioned parties
    text: 'you are not: (i) identified on any list of restricted parties targeted under U.S., EU, Canadian, or multilateral sanctions'
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
name: Kabam
provenance_date: '2026-11-09'
provider_name: Kabam
provider_slug: kabam
slug: kabam-eligibility
source_date: '2026-11-09'
source_filename: kabam-eligibility.yml
source_heading: Eligibility
source_page: https://kabam.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kabam\naid: kabam\nurl: https://kabam.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a natural person and, subject to Section 1.2 (Minors) below, an adult of the legal age of majority\n    in your country, province and/or state of residence to use and access the Services\nrestricted_uses:\n- summary: Sanctioned parties\n  text: 'you are not: (i) identified on any list of restricted parties targeted under U.S., EU, Canadian, or multilateral\n    sanctions'\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: In no event will you be able to install, use, or otherwise access the Services (including creating an Account)\n    if you are under the age of thirteen (13).\n"
source_yaml_url: https://artifacts.apis.io/kabam/eligibility/kabam-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Kabam's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Mobile Games
- Video Games
- Entertainment
- Mobile
---
