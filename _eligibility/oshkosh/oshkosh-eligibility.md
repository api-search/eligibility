---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is availble only to individuals and/or entities acting in a professional capacity (non-consumers).
    type: individual
  - text: The Site is availble only to individuals and/or entities acting in a professional capacity (non-consumers).
    type: business
  minimum_age:
    text: The Site is not intended for anyone under the age of 16
    value: '16'
  restricted_uses:
  - summary: Consumer use
    text: The Site is availble only to individuals and/or entities acting in a professional capacity (non-consumers).
  - summary: Commercial solicitation
    text: using the Site for any commercial solicitation purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Oshkosh reserves the right, in its sole discretion, to deny any request to become a registered user
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Oshkosh
provenance_date: '2026-11-10'
provider_name: Oshkosh
provider_slug: oshkosh
slug: oshkosh-eligibility
source_date: '2026-11-10'
source_filename: oshkosh-eligibility.yml
source_heading: Eligibility
source_page: https://www.oshkoshcorp.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oshkosh\naid: oshkosh\nurl: https://www.oshkoshcorp.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is availble only to individuals and/or entities acting in a professional capacity (non-consumers).\n- type: business\n  text: The Site is availble only to individuals and/or entities acting in a professional capacity (non-consumers).\nrestricted_uses:\n- summary: Consumer use\n  text: The Site is availble only to individuals and/or entities acting in a professional capacity (non-consumers).\n- summary: Commercial\
  \ solicitation\n  text: using the Site for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Oshkosh reserves the right, in its sole discretion, to deny any request to become a registered user\nminimum_age:\n  value: '16'\n  text: The Site is not intended for anyone under the age of 16\n"
source_yaml_url: https://artifacts.apis.io/oshkosh/eligibility/oshkosh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Oshkosh's own page on 2026-11-10.
synthetic: false
tags:
- Defense
- Fortune 500
- Industrial
- Manufacturing
- Vehicles
---
