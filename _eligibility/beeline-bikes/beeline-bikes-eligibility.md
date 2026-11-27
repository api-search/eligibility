---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Beeline's Website and Services are intended only for users located in the United States and Canada.
  minimum_age:
    text: you represent and warrant that you are of legal age to form a binding contract with Beeline
    value: null
  restricted_uses:
  - summary: No commercial purposes
    text: You are prohibited from accessing or using for any commercial purposes any part of the Website or any Services or materials available through the Website.
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
name: Beeline Bikes
provenance_date: '2026-11-09'
provider_name: Beeline Bikes
provider_slug: beeline-bikes
slug: beeline-bikes-eligibility
source_date: '2026-11-09'
source_filename: beeline-bikes-eligibility.yml
source_heading: Eligibility
source_page: https://beelineconnect.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beeline Bikes\naid: beeline-bikes\nurl: https://beelineconnect.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Beeline's Website and Services are intended only for users located in the United States and Canada.\nentity_types: []\nrestricted_uses:\n- summary: No commercial purposes\n  text: You are prohibited from accessing or using for any commercial purposes any part of the Website or any Services\n    or materials available through the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: you represent and warrant that you are of legal age to form a binding contract with Beeline\n"
source_yaml_url: https://artifacts.apis.io/beeline-bikes/eligibility/beeline-bikes-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Beeline Bikes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Bicycle
- Retail
- Marketplace
- Scheduling
- Inventory
- Warranty
- Logistics
---
