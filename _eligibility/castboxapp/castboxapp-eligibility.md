---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are of sufficient legal age or otherwise have legal capacity to legally enter into these ToS.
    type: individual
  minimum_age:
    text: You are over the age of 16 or, if not, you are between the ages of 13 and 16 and a third party parent or legal guardian has agreed to these ToS.
    value: '13'
  restricted_uses:
  - summary: No advertising in Contributions
    text: will not post Contributions that contain advertisements or solicit any person to buy or sell products or services
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
name: Castbox
provenance_date: '2026-11-09'
provider_name: Castbox
provider_slug: castboxapp
slug: castboxapp-eligibility
source_date: '2026-11-09'
source_filename: castboxapp-eligibility.yml
source_heading: Eligibility
source_page: https://castbox.fm/termsofservice.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Castbox\naid: castboxapp\nurl: https://castbox.fm/termsofservice.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are of sufficient legal age or otherwise have legal capacity to legally enter into these ToS.\nrestricted_uses:\n- summary: No advertising in Contributions\n  text: will not post Contributions that contain advertisements or solicit any person to buy or sell products or\n    services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are over\
  \ the age of 16 or, if not, you are between the ages of 13 and 16 and a third party parent or\n    legal guardian has agreed to these ToS.\n"
source_yaml_url: https://artifacts.apis.io/castboxapp/eligibility/castboxapp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Castbox's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Podcasts
- Audio
- Media
- Streaming
- Content
- Consumer
---
