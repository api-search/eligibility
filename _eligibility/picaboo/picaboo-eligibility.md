---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Agreement is void where prohibited by law and the right to use the Technology in such jurisdictions is revoked.
  entity_types:
  - text: Licensee must be at least 13 years of age.
    type: individual
  minimum_age:
    text: Licensee must be at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Personal, non-commercial, internal use only
    text: only for its personal, non-commercial, internal use
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
name: Picaboo
provenance_date: '2026-11-10'
provider_name: Picaboo
provider_slug: picaboo
slug: picaboo-eligibility
source_date: '2026-11-10'
source_filename: picaboo-eligibility.yml
source_heading: Eligibility
source_page: https://www.picaboo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Picaboo\naid: picaboo\nurl: https://www.picaboo.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Agreement is void where prohibited by law and the right to use the Technology in such jurisdictions\n    is revoked.\nentity_types:\n- type: individual\n  text: Licensee must be at least 13 years of age.\nrestricted_uses:\n- summary: Personal, non-commercial, internal use only\n  text: only for its personal, non-commercial, internal use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Licensee must be\
  \ at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/picaboo/eligibility/picaboo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Picaboo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Photos
- Printing
- E-Commerce
- Software-as-a-Service
---
