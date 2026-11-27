---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Traders Union does not guarantee that the Website or any content published on it is available or suitable for use in all jurisdictions.
  entity_types:
  - text: The Website is intended for use by persons who are legally permitted, under the laws of their jurisdiction, to access informational and educational content.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use violating local law
    text: The information on this website is not intended for distribution or use by any person in any country or jurisdiction, where such distribution or use would be in violation of the local law or regulation.
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
name: Traders Union
provenance_date: '2026-11-10'
provider_name: Traders Union
provider_slug: tradersunion
slug: tradersunion-eligibility
source_date: '2026-11-10'
source_filename: tradersunion-eligibility.yml
source_heading: Eligibility
source_page: https://tradersunion.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Traders Union\naid: tradersunion\nurl: https://tradersunion.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Traders Union does not guarantee that the Website or any content published on it is available or suitable\n    for use in all jurisdictions.\nentity_types:\n- type: individual\n  text: The Website is intended for use by persons who are legally permitted, under the laws of their jurisdiction,\n    to access informational and educational content.\nrestricted_uses:\n- summary: Use violating local law\n  text: The information on this website is not intended for\
  \ distribution or use by any person in any country or\n    jurisdiction, where such distribution or use would be in violation of the local law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tradersunion/eligibility/tradersunion-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Traders Union's own page on 2026-11-10.
synthetic: false
tags:
- Financial News
- Broker Reviews
- Trading Guides
- Market Data
- Cryptocurrency
- Foreign Exchange
- Prop Trading
---
