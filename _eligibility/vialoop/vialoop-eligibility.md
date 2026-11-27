---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have the legal capacity to enter into binding contracts to use our Services.
    value: '18'
  restricted_uses:
  - summary: Unauthorized tracking
    text: Unauthorized tracking is illegal and may result in civil and criminal penalties.
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
name: ViaLoop
provenance_date: '2026-11-10'
provider_name: ViaLoop
provider_slug: vialoop
slug: vialoop-eligibility
source_date: '2026-11-10'
source_filename: vialoop-eligibility.yml
source_heading: Eligibility
source_page: https://vialoop.in/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ViaLoop\naid: vialoop\nurl: https://vialoop.in/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Unauthorized tracking\n  text: Unauthorized tracking is illegal and may result in civil and criminal penalties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years old and have the legal capacity to enter into binding contracts to use our\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/vialoop/eligibility/vialoop-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ViaLoop's own page on 2026-11-10.
synthetic: false
tags:
- Vehicle Tracking
- OBD Device
- Fuel Monitoring
- Driver Safety
- Car Sharing
- Multi‑vehicle
- GPS Tracking
---
