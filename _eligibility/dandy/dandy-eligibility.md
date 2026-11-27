---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is provided solely for informational purposes for dental professionals and their personnel.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No patient health information
    text: The Site is not intended for the transmission, storage, review or receipt of confidential Patient Health Information.
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
name: Dandy
provenance_date: '2026-11-09'
provider_name: Dandy
provider_slug: dandy
slug: dandy-eligibility
source_date: '2026-11-09'
source_filename: dandy-eligibility.yml
source_heading: Eligibility
source_page: https://www.meetdandy.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dandy\naid: dandy\nurl: https://www.meetdandy.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Site is provided solely for informational purposes for dental professionals and their personnel.\nrestricted_uses:\n- summary: No patient health information\n  text: The Site is not intended for the transmission, storage, review or receipt of confidential Patient Health\n    Information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/dandy/eligibility/dandy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dandy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Dental
- Digital Dentistry
- Dental Lab
- Healthcare
- Health Tech
- Intraoral Scanners
- Orthodontics
- Manufacturing
- DSO
---
