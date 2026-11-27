---
claim_count: 2
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
  - source: https://www.hydroone.com/terms-of-use
    summary: Indemnity for use and violations
    text: You agree to indemnify, defend and hold harmless Hydro One and its affiliates
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: HONI will review and approve or decline Applicant registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hydro One
provenance_date: '2026-11-09'
provider_name: Hydro One
provider_slug: hydro-one
slug: hydro-one-eligibility
source_date: '2026-11-09'
source_filename: hydro-one-eligibility.yml
source_heading: Eligibility
source_page: https://www.hydroone.com/saving-money-and-energy/green-button/third-party-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hydro One\naid: hydro-one\nurl: https://www.hydroone.com/saving-money-and-energy/green-button/third-party-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.hydroone.com/saving-money-and-energy/green-button/third-party-terms-and-conditions\n  - https://www.hydroone.com/terms-of-use\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Indemnity for use and violations\n  text: You agree to indemnify, defend and hold harmless Hydro One and its affiliates\n  source: https://www.hydroone.com/terms-of-use\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: true\n  text: HONI will review and approve or decline Applicant registration.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hydro-one/eligibility/hydro-one-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Hydro One's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Canada
- Utilities
- Electricity
- Grid
- Smart Metering
- Green Button
- Energy Data
- Transmission
- Distribution
---
