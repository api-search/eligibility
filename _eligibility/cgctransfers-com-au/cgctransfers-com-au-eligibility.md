---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Children under 12 must be accompanied by an adult.
    value: null
  restricted_uses:
  - summary: Children under 12 need an adult
    text: Children under 12 must be accompanied by an adult.
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
name: CGC Airport Transfers
provenance_date: '2026-11-09'
provider_name: CGC Airport Transfers
provider_slug: cgctransfers-com-au
slug: cgctransfers-com-au-eligibility
source_date: '2026-11-09'
source_filename: cgctransfers-com-au-eligibility.yml
source_heading: Eligibility
source_page: https://cgctransfers.com.au/bookingtermsandconditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CGC Airport Transfers\naid: cgctransfers-com-au\nurl: https://cgctransfers.com.au/bookingtermsandconditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Children under 12 need an adult\n  text: Children under 12 must be accompanied by an adult.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Children under 12 must be accompanied by an adult.\n"
source_yaml_url: https://artifacts.apis.io/cgctransfers-com-au/eligibility/cgctransfers-com-au-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from CGC Airport Transfers's own page on 2026-11-09.
synthetic: false
tags:
- Airport Transfers
- Private Transport
- Australia
- GoldCoast
- Brisbane
---
