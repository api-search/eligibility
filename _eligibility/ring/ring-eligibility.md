---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use any Ring Offerings if you are the subject of U.S. sanctions or of sanctions consistent with U.S. law imposed by the governments of the country where you are using the Ring Offerings.
  entity_types:
  - text: You must be at least 13 years old to use the Ring Offerings. If you are between the ages of 13 and 18, you may use the Ring Offerings only with consent of a parent or guardian who agrees to this Agreement on your behalf.
    type: individual
  - text: If you are a business that purchased a Ring Offering for business purposes (such as using Ring Offerings on your business premises or enabling tenants to use the Ring Offerings)
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Ring Offerings.
    value: '13'
  restricted_uses:
  - summary: Sanctioned users
    text: You may not use any Ring Offerings if you are the subject of U.S. sanctions or of sanctions consistent with U.S. law imposed by the governments of the country where you are using the Ring Offerings.
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
name: Ring
provenance_date: '2026-11-10'
provider_name: Ring
provider_slug: ring
slug: ring-eligibility
source_date: '2026-11-10'
source_filename: ring-eligibility.yml
source_heading: Eligibility
source_page: https://ring.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ring\naid: ring\nurl: https://ring.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use any Ring Offerings if you are the subject of U.S. sanctions or of sanctions consistent with\n    U.S. law imposed by the governments of the country where you are using the Ring Offerings.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Ring Offerings. If you are between the ages of 13 and 18, you\n    may use the Ring Offerings only with consent of a parent or guardian who agrees to this Agreement on your behalf.\n- type: business\n\
  \  text: If you are a business that purchased a Ring Offering for business purposes (such as using Ring Offerings\n    on your business premises or enabling tenants to use the Ring Offerings)\nrestricted_uses:\n- summary: Sanctioned users\n  text: You may not use any Ring Offerings if you are the subject of U.S. sanctions or of sanctions consistent with\n    U.S. law imposed by the governments of the country where you are using the Ring Offerings.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Ring Offerings.\n"
source_yaml_url: https://artifacts.apis.io/ring/eligibility/ring-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ring's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Home Security
- Smart Home
- IoT
- Video
- Camera
- Doorbells
- Webhook
- WebRTC
- Amazon
- Developer Platform
- MCP
---
