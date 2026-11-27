---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access this Website from outside of the United States, you are solely responsible for ensuring compliance with the laws of your specific jurisdiction.
  minimum_age:
    text: (v) if you are under thirteen (13) years of age
    value: '13'
  restricted_uses:
  - summary: Unlawful or damaging use
    text: You may not use the Website (i) for any purpose that violates applicable federal, state or local laws, regulations or rules
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
name: AeroFarms
provenance_date: '2026-11-09'
provider_name: AeroFarms
provider_slug: aerofarms
slug: aerofarms-eligibility
source_date: '2026-11-09'
source_filename: aerofarms-eligibility.yml
source_heading: Eligibility
source_page: https://www.aerofarms.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AeroFarms\naid: aerofarms\nurl: https://www.aerofarms.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access this Website from outside of the United States, you are solely responsible for ensuring compliance\n    with the laws of your specific jurisdiction.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or damaging use\n  text: You may not use the Website (i) for any purpose that violates applicable federal, state or local laws, regulations\n    or rules\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: (v) if you are under thirteen (13) years of age\n"
source_yaml_url: https://artifacts.apis.io/aerofarms/eligibility/aerofarms-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AeroFarms's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Vertical Farming
- Indoor Farming
- AgTech
- Food and Beverage
- Consumer Packaged Goods
- Microgreens
- Sustainability
- Content
- Commerce
- MCP
---
