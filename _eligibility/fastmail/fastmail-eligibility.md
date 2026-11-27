---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are provided only to individuals who are 18 years old or older.
    type: individual
  - text: You are authorised to use the Services for business-related communications
    type: business
  minimum_age:
    text: The Services are provided only to individuals who are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Not for automated or transactional email
    text: The Services are not designed for sending automated or transactional emails.
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
name: Fastmail
provenance_date: '2026-11-09'
provider_name: Fastmail
provider_slug: fastmail
slug: fastmail-eligibility
source_date: '2026-11-09'
source_filename: fastmail-eligibility.yml
source_heading: Eligibility
source_page: https://www.fastmail.com/policies/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fastmail\naid: fastmail\nurl: https://www.fastmail.com/policies/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are provided only to individuals who are 18 years old or older.\n- type: business\n  text: You are authorised to use the Services for business-related communications\nrestricted_uses:\n- summary: Not for automated or transactional email\n  text: The Services are not designed for sending automated or transactional emails.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: '18'\n  text: The Services are provided only to individuals who are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/fastmail/eligibility/fastmail-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fastmail's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Privacy
- Security
- Business
- Cloud
---
