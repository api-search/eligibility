---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You will not use or otherwise transport, export or re-export the SDK and/or our Service into any country forbidden to receive the SDK and/or our Service by any U.S. or other jurisdictions’ export or technology laws
  entity_types:
  - text: If you are entering into this Agreement on behalf of a legal entity, you represent and warrant that you are authorized to bind such legal entity
    type: business
  minimum_age:
    text: and in any event are not under the age of 13
    value: '13'
  restricted_uses:
  - summary: Competitors barred
    text: you are our direct competitor, except with our prior written consent
  - summary: Children's data
    text: you will not transmit any “Personal Information” (as defined under COPPA) about or relating to an individual under the age of 13 to the Service
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
name: Oriient
provenance_date: '2026-11-10'
provider_name: Oriient
provider_slug: oriient
slug: oriient-eligibility
source_date: '2026-11-10'
source_filename: oriient-eligibility.yml
source_heading: Eligibility
source_page: https://www.oriient.me/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oriient\naid: oriient\nurl: https://www.oriient.me/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You will not use or otherwise transport, export or re-export the SDK and/or our Service into any country\n    forbidden to receive the SDK and/or our Service by any U.S. or other jurisdictions’ export or technology laws\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a legal entity, you represent and warrant that you\n    are authorized to bind such legal entity\nrestricted_uses:\n- summary: Competitors barred\n  text:\
  \ you are our direct competitor, except with our prior written consent\n- summary: Children's data\n  text: you will not transmit any “Personal Information” (as defined under COPPA) about or relating to an individual\n    under the age of 13 to the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: and in any event are not under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/oriient/eligibility/oriient-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Oriient's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Indoor Positioning
- Indoor Navigation
- Location Services
- Geolocation
- SDK
- Retail
- Asset Tracking
---
