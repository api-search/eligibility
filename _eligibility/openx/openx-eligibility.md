---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are at least 18 years of age or between the ages of 13 and 17 and using the OpenX Website with parental or legal guardian consent and supervision
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
name: OpenX
provenance_date: '2026-11-10'
provider_name: OpenX
provider_slug: openx
slug: openx-eligibility
source_date: '2026-11-10'
source_filename: openx-eligibility.yml
source_heading: Eligibility
source_page: https://www.openx.com/legal/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenX\naid: openx\nurl: https://www.openx.com/legal/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are at least 18 years of age or between the ages of 13 and 17 and using the OpenX Website with parental\n    or legal guardian consent and supervision\n"
source_yaml_url: https://artifacts.apis.io/openx/eligibility/openx-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from OpenX's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Programmatic Advertising
- Ad Exchange
- Supply Side Platform
- Real-Time Bidding
- OpenRTB
- Header Bidding
- Prebid
- AdTech
- CTV
- Video Advertising
- Display Advertising
- Curation
- Identity
- GraphQL
- gRPC
- MCP
- Reporting
- Audience Targeting
---
