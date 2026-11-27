---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Wi-Fi network is intended for use by individuals aged 13 or older, unless expressly permitted by the Venue.
    type: individual
  minimum_age:
    text: The Wi-Fi network is intended for use by individuals aged 13 or older, unless expressly permitted by the Venue.
    value: '13'
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
name: SocialSign.in
provenance_date: '2026-11-10'
provider_name: SocialSign.in
provider_slug: socialsignin
slug: socialsignin-eligibility
source_date: '2026-11-10'
source_filename: socialsignin-eligibility.yml
source_heading: Eligibility
source_page: https://socialsign.in/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SocialSign.in\naid: socialsignin\nurl: https://socialsign.in/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Wi-Fi network is intended for use by individuals aged 13 or older, unless expressly permitted by the\n    Venue.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Wi-Fi network is intended for use by individuals aged 13 or older, unless expressly permitted by the\n    Venue.\n"
source_yaml_url: https://artifacts.apis.io/socialsignin/eligibility/socialsignin-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from SocialSign.in's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Guest WiFi
- WiFi Marketing
- Captive Portal
- Customer Data Platform
- Location Analytics
- Retail Media
- Marketing
---
