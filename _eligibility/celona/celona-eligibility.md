---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Site and its contents are solely for your own personal non-commercial use.
    type: individual
  minimum_age:
    text: MATERIALS, SERVICES AND INFORMATION INTENDED FOR USERS OF THE SITE ARE NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE.
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: This Site and its contents are solely for your own personal non-commercial use.
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
name: Celona
provenance_date: '2026-11-09'
provider_name: Celona
provider_slug: celona
slug: celona-eligibility
source_date: '2026-11-09'
source_filename: celona-eligibility.yml
source_heading: Eligibility
source_page: https://celona.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Celona\naid: celona\nurl: https://celona.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Site and its contents are solely for your own personal non-commercial use.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: This Site and its contents are solely for your own personal non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: MATERIALS, SERVICES AND INFORMATION INTENDED FOR USERS OF THE SITE ARE NOT FOR USE BY CHILDREN\
  \ UNDER 13\n    YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/celona/eligibility/celona-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Celona's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Networking
- Private Cellular
- 5G
- LTE
- CBRS
- Wireless
- Network Monitoring
- Telecommunications
- IoT
---
