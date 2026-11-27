---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual with a registered Wingtra account in their name, with use limited to such individual
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Service, including Wingtra Software.
    value: '18'
  restricted_uses:
  - summary: Flight operations in restricted or safety-sensitive areas
    text: Wingtra may limit or disable the operation of the Wingtra Hardware in locations that raise safety or security concerns
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Wingtra may verify your account by reviewing the validity of a personal credential, such as a payment card or mobile phone number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wingtra
provenance_date: '2026-11-10'
provider_name: Wingtra
provider_slug: wingtra
slug: wingtra-eligibility
source_date: '2026-11-10'
source_filename: wingtra-eligibility.yml
source_heading: Eligibility
source_page: https://wingtra.com/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wingtra\naid: wingtra\nurl: https://wingtra.com/eula/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual with a registered Wingtra account in their name, with use limited to such individual\nrestricted_uses:\n- summary: Flight operations in restricted or safety-sensitive areas\n  text: Wingtra may limit or disable the operation of the Wingtra Hardware in locations that raise safety or security\n    concerns\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Wingtra may verify your account by reviewing\
  \ the validity of a personal credential, such as a payment card\n    or mobile phone number.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service, including Wingtra Software.\n"
source_yaml_url: https://artifacts.apis.io/wingtra/eligibility/wingtra-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Wingtra's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Drones
- UAV
- Aerial Surveying
- Mapping
- Photogrammetry
- Geospatial
- Surveying
- LiDAR
- Hardware
- Switzerland
---
