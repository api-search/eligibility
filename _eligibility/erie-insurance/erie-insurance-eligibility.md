---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Content and Site are based in the Commonwealth of Pennsylvania in the United States and provided for access and use only by persons located in the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for states where ERIE is unlicensed
    text: The Site is not intended to, and may not be used to, provide information regarding insurance products in any state where ERIE is not licensed to do business.
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
name: Erie Insurance
provenance_date: '2026-11-09'
provider_name: Erie Insurance
provider_slug: erie-insurance
slug: erie-insurance-eligibility
source_date: '2026-11-09'
source_filename: erie-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.erieinsurance.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Erie Insurance\naid: erie-insurance\nurl: https://www.erieinsurance.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Content and Site are based in the Commonwealth of Pennsylvania in the United States and provided for\n    access and use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Not for states where ERIE is unlicensed\n  text: The Site is not intended to, and may not be used to, provide information regarding insurance products in\n    any state where ERIE is not licensed to do business.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/erie-insurance/eligibility/erie-insurance-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Erie Insurance's own page on 2026-11-09.
synthetic: false
tags:
- Auto Insurance
- Fortune 500
- Home Insurance
- Insurance
- Business Insurance
- Life Insurance
- Property and Casualty
---
