---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: will only use the Service for purchases within the United States of America
  minimum_age:
    text: you (i) are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Competing services excluded
    text: You shall not access the Service if you sell or provide any service or software that may compete with Dwellsy’s services or software
  - summary: Fair housing and anti-discrimination compliance
    text: compliance with all anti-discrimination and fair housing laws, as applicable
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
name: Dwellsy
provenance_date: '2026-11-09'
provider_name: Dwellsy
provider_slug: dwellsy
slug: dwellsy-eligibility
source_date: '2026-11-09'
source_filename: dwellsy-eligibility.yml
source_heading: Eligibility
source_page: https://dwellsy.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dwellsy\naid: dwellsy\nurl: https://dwellsy.com/pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: will only use the Service for purchases within the United States of America\nentity_types: []\nrestricted_uses:\n- summary: Competing services excluded\n  text: You shall not access the Service if you sell or provide any service or software that may compete with Dwellsy’s\n    services or software\n- summary: Fair housing and anti-discrimination compliance\n  text: compliance with all anti-discrimination and fair housing laws, as applicable\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you (i) are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/dwellsy/eligibility/dwellsy-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dwellsy's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
