---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is offered and available to users who reside in the United States or any of its territories or possessions
  entity_types:
  - text: intended for users 16 years of age or older
    type: individual
  minimum_age:
    text: intended for users 16 years of age or older
    value: '16'
  restricted_uses:
  - summary: Commercial use prohibited
    text: You must not access or use for any commercial purposes any part of the Website or any services or materials available through the Website.
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
name: LIVEKINDLY
provenance_date: '2026-11-09'
provider_name: LIVEKINDLY
provider_slug: livekindly
slug: livekindly-eligibility
source_date: '2026-11-09'
source_filename: livekindly-eligibility.yml
source_heading: Eligibility
source_page: https://thelivekindlyco.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LIVEKINDLY\naid: livekindly\nurl: https://thelivekindlyco.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is offered and available to users who reside in the United States or any of its territories\n    or possessions\nentity_types:\n- type: individual\n  text: intended for users 16 years of age or older\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: You must not access or use for any commercial purposes any part of the Website or any services or materials\n    available through the Website.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: intended for users 16 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/livekindly/eligibility/livekindly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LIVEKINDLY's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food and Beverage
- Plant-Based
- Alternative Protein
- Consumer Packaged Goods
- Sustainability
- Manufacturing
- Retail
- Content
- Newsroom
---
