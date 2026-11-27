---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged thirteen (13) years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged thirteen (13) years or older.
    value: '13'
  restricted_uses:
  - summary: Prohibited User Submissions
    text: 'You agree that you will not display, post, submit, publish, upload or transmit a User Submission that:'
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
name: PlainID
provenance_date: '2026-11-10'
provider_name: PlainID
provider_slug: plainid
slug: plainid-eligibility
source_date: '2026-11-10'
source_filename: plainid-eligibility.yml
source_heading: Eligibility
source_page: https://www.plainid.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PlainID\naid: plainid\nurl: https://www.plainid.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\nrestricted_uses:\n- summary: Prohibited User Submissions\n  text: 'You agree that you will not display, post, submit, publish, upload or transmit a User Submission that:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is only intended for individuals aged thirteen\
  \ (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/plainid/eligibility/plainid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PlainID's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Authorization
- Access Control
- PBAC
- Identity
- Policy Management
- API Security
---
