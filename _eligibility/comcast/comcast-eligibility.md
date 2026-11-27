---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity that is creating an account and accepting the terms of this Agreement
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use of data outside customer permissions
    text: request, use or make available any data obtained using the Authentication API outside any permissions expressly granted by Comcast customers in connection with using Authorized Products
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Comcast, in its sole discretion, will issue Company an API key that identifies Company and enables Company to access the Authentication API
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Comcast
provenance_date: '2026-11-09'
provider_name: Comcast
provider_slug: comcast
slug: comcast-eligibility
source_date: '2026-11-09'
source_filename: comcast-eligibility.yml
source_heading: Eligibility
source_page: https://developers.xfinity.com/TOS.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comcast\naid: comcast\nurl: https://developers.xfinity.com/TOS.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: the entity that is creating an account and accepting the terms of this Agreement\nrestricted_uses:\n- summary: No use of data outside customer permissions\n  text: request, use or make available any data obtained using the Authentication API outside any permissions expressly\n    granted by Comcast customers in connection with using Authorized Products\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n\
  \  text: Comcast, in its sole discretion, will issue Company an API key that identifies Company and enables Company\n    to access the Authentication API\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/comcast/eligibility/comcast-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Comcast's own page on 2026-11-09.
synthetic: false
tags:
- Cable
- Connected Devices
- Entertainment
- Internet
- Media
- Mobile
- Streaming
- Wireless
- Fortune 100
- Telecommunications
---
