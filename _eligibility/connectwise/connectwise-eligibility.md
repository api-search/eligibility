---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - LY
    - KP
    - SD
    - SY
    served: []
    text: The Services and products may not be downloaded or provided into Cuba, Iran, Libya, North Korea, Sudan, Syria or any other country subject to U.S. trade sanctions
  entity_types:
  - text: The Site has been developed exclusively for use by ConnectWise partners, prospective partners, media, vendor partners and ConnectWise employees.
    type: business
  minimum_age:
    text: Minors are not eligible to use the Site, and we ask that they do not submit any personal information to us.
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You agree to comply with all export laws and restrictions and regulations of any United States or foreign agency or authority
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- LY
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ConnectWise
provenance_date: '2026-11-09'
provider_name: ConnectWise
provider_slug: connectwise
slug: connectwise-eligibility
source_date: '2026-11-09'
source_filename: connectwise-eligibility.yml
source_heading: Eligibility
source_page: https://www.connectwise.com/company/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ConnectWise\naid: connectwise\nurl: https://www.connectwise.com/company/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - LY\n  - KP\n  - SD\n  - SY\n  text: The Services and products may not be downloaded or provided into Cuba, Iran, Libya, North Korea, Sudan,\n    Syria or any other country subject to U.S. trade sanctions\nentity_types:\n- type: business\n  text: The Site has been developed exclusively for use by ConnectWise partners, prospective partners, media, vendor\n    partners and ConnectWise employees.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n\
  \  text: You agree to comply with all export laws and restrictions and regulations of any United States or foreign\n    agency or authority\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Minors are not eligible to use the Site, and we ask that they do not submit any personal information to\n    us.\n"
source_yaml_url: https://artifacts.apis.io/connectwise/eligibility/connectwise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ConnectWise's own page on 2026-11-09.
synthetic: false
tags:
- IT Management
- MSP
- PSA
- RMM
- Remote Access
- Cybersecurity
---
