---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned or debarred parties
    text: You agree that you are not an individual, or an individual employed by or otherwise associated with an entity, identified on the U.S. Department of Commerce’s Denied Persons, Unverified or Entity Lists, the U.S. Department of Treasury’s Specially Designated Nationals Lists, or the Department of State’s Debarred Parties List
  - summary: Medical or life-support applications
    text: QuickLogic products are not designed, intended, authorized, or warranted for use as components in systems intended for surgical implant in the body, or in other applications intended to support or sustain life
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You agree that you are not an individual, or an individual employed by or otherwise associated with an entity, identified on the U.S. Department of Commerce’s Denied Persons, Unverified or Entity Lists
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: QuickLogic
provenance_date: '2026-11-10'
provider_name: QuickLogic
provider_slug: quicklogic
slug: quicklogic-eligibility
source_date: '2026-11-10'
source_filename: quicklogic-eligibility.yml
source_heading: Eligibility
source_page: https://www.quicklogic.com/legal-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QuickLogic\naid: quicklogic\nurl: https://www.quicklogic.com/legal-notice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned or debarred parties\n  text: You agree that you are not an individual, or an individual employed by or otherwise associated with an entity,\n    identified on the U.S. Department of Commerce’s Denied Persons, Unverified or Entity Lists, the U.S. Department\n    of Treasury’s Specially Designated Nationals Lists, or the Department of State’s Debarred Parties List\n- summary: Medical or life-support\
  \ applications\n  text: QuickLogic products are not designed, intended, authorized, or warranted for use as components in systems\n    intended for surgical implant in the body, or in other applications intended to support or sustain life\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You agree that you are not an individual, or an individual employed by or otherwise associated with an entity,\n    identified on the U.S. Department of Commerce’s Denied Persons, Unverified or Entity Lists\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quicklogic/eligibility/quicklogic-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from QuickLogic's own page on 2026-11-10.
synthetic: false
tags:
- eFPGA
- FPGA
- Semiconductors
- Custom FPGA
- Rad‑Hard
- Chiplets
- Security
- Development Boards
---
