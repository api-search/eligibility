---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information on this website is intended for our Australian customers
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: authorised to access the content for your personal and non-commercial use only
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
name: Jemena
provenance_date: '2026-11-09'
provider_name: Jemena
provider_slug: jemena
slug: jemena-eligibility
source_date: '2026-11-09'
source_filename: jemena-eligibility.yml
source_heading: Eligibility
source_page: https://www.jemena.com.au/about-us/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jemena\naid: jemena\nurl: https://www.jemena.com.au/about-us/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information on this website is intended for our Australian customers\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: authorised to access the content for your personal and non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jemena/eligibility/jemena-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Jemena's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Australia
- Utilities
- Electricity
- Gas
- Grid
- Network Distributor
- DER
- Solar
- Smart Metering
- Demand Response
- IEEE 2030.5
---
