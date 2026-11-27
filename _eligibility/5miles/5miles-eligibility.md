---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - SD
    - SY
    - KP
    served: []
    text: Banned Parties include ... persons who are citizens of, or located within, a nation that is subject to U.S. trade sanctions, embargoes or other significant trade restrictions (including, without limitation, Cuba, Iran, Sudan, Syria and North Korea)
  entity_types:
  - text: You will only use the Services for your own personal use, and not on behalf of or for the benefit of any third party
    type: individual
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on its behalf
    type: business
  minimum_age:
    text: using our Services if you are not able to form legally binding contracts (for example if you are under 18)
    value: '18'
  restricted_uses:
  - summary: Prohibited items
    text: posting, listing, or uploading items for sale that are generally illegal to own or possess
  - summary: Sanctioned parties and countries
    text: 5miles does not do business with or otherwise engage in or facilitate transactions involving Banned Parties.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- SD
- SY
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 5miles
provenance_date: '2026-11-09'
provider_name: 5miles
provider_slug: 5miles
slug: 5miles-eligibility
source_date: '2026-11-09'
source_filename: 5miles-eligibility.yml
source_heading: Eligibility
source_page: https://www.5miles.com/info/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 5miles\naid: 5miles\nurl: https://www.5miles.com/info/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - SD\n  - SY\n  - KP\n  text: Banned Parties include ... persons who are citizens of, or located within, a nation that is subject to U.S.\n    trade sanctions, embargoes or other significant trade restrictions (including, without limitation, Cuba, Iran,\n    Sudan, Syria and North Korea)\nentity_types:\n- type: individual\n  text: You will only use the Services for your own personal use, and not on behalf of or for the benefit of any\n    third party\n\
  - type: business\n  text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on its behalf\nrestricted_uses:\n- summary: Prohibited items\n  text: posting, listing, or uploading items for sale that are generally illegal to own or possess\n- summary: Sanctioned parties and countries\n  text: 5miles does not do business with or otherwise engage in or facilitate transactions involving Banned Parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: using our Services if you are not able to form legally binding contracts (for example if you are under 18)\n"
source_yaml_url: https://artifacts.apis.io/5miles/eligibility/5miles-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from 5miles's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Classifieds
- E-Commerce
- Local Commerce
- Mobile App
- Consumer
- Secondhand
---
