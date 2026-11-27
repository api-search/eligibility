---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: These Services are controlled, operated and administered by Plixer from its offices in the United States of America. Plixer makes no representation that the Services or Materials are appropriate or available for use at other locations outside the United States, and access to the Services from jurisdictions where the Services or Materials are illegal is prohibited.
  minimum_age:
    text: you affirm that you are over the age of 13 and acknowledge that these Services were not intended for children under 13.
    value: '13'
  restricted_uses:
  - summary: Export control compliance
    text: You shall comply with these laws and regulations and shall not, without prior U.S. government authorization, export, reexport, or transfer Plixer products, services or technology
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
name: Plixer
provenance_date: '2026-11-10'
provider_name: Plixer
provider_slug: plixer
slug: plixer-eligibility
source_date: '2026-11-10'
source_filename: plixer-eligibility.yml
source_heading: Eligibility
source_page: https://www.plixer.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plixer\naid: plixer\nurl: https://www.plixer.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: These Services are controlled, operated and administered by Plixer from its offices in the United States\n    of America. Plixer makes no representation that the Services or Materials are appropriate or available for use\n    at other locations outside the United States, and access to the Services from jurisdictions where the Services\n    or Materials are illegal is prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Export control compliance\n  text: You shall comply\
  \ with these laws and regulations and shall not, without prior U.S. government authorization,\n    export, reexport, or transfer Plixer products, services or technology\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you affirm that you are over the age of 13 and acknowledge that these Services were not intended for children\n    under 13.\n"
source_yaml_url: https://artifacts.apis.io/plixer/eligibility/plixer-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Plixer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Network Observability
- Network Security
- Network Detection and Response
- NetFlow
- IPFIX
- Network Traffic Analysis
- Cybersecurity
---
