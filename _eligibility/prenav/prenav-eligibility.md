---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use the Sites if you are located in a country embargoed by the United States, or if you are on the United States Treasury Department's list of Specially Designated Nationals.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harassment, unlawful content, impersonation
    text: Use the Sites to harass, abuse, or harm, or advocate or incite harassment towards, another person or group
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some parts of the Sites may require that you open and maintain an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prenav
provenance_date: '2026-11-10'
provider_name: Prenav
provider_slug: prenav
slug: prenav-eligibility
source_date: '2026-11-10'
source_filename: prenav-eligibility.yml
source_heading: Eligibility
source_page: https://www.prenav.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prenav\naid: prenav\nurl: https://www.prenav.com/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use the Sites if you are located in a country embargoed by the United States, or if you are on the United\n    States Treasury Department's list of Specially Designated Nationals.\nentity_types: []\nrestricted_uses:\n- summary: Harassment, unlawful content, impersonation\n  text: Use the Sites to harass, abuse, or harm, or advocate or incite harassment towards, another person or group\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some parts of\
  \ the Sites may require that you open and maintain an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prenav/eligibility/prenav-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Prenav's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Drones
- Infrastructure Inspection
- Digital Twin
- Deep Learning
- Computer Vision
- Photogrammetry
- Synthetic Data
- Asset Management
- Construction Technology
---
