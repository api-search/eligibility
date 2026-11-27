---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an entity, then you represent and warrant that you have the authority to bind that entity or organization to these Terms
    type: business
  minimum_age:
    text: by using the Wink App, you affirm that either you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No child exploitation content
    text: We do not permit the Wink Platform to be used to publish, submit/receive, upload/download, post, use, copy or otherwise produce, transmit, distribute or store child pornography or content otherwise depicting child exploitation.
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
name: 9 Count
provenance_date: '2026-11-09'
provider_name: 9 Count
provider_slug: 9count
slug: 9count-eligibility
source_date: '2026-11-09'
source_filename: 9count-eligibility.yml
source_heading: Eligibility
source_page: https://www.getwinkapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 9 Count\naid: 9count\nurl: https://www.getwinkapp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an entity, then you represent and warrant that you have the authority\n    to bind that entity or organization to these Terms\nrestricted_uses:\n- summary: No child exploitation content\n  text: We do not permit the Wink Platform to be used to publish, submit/receive, upload/download, post, use, copy\n    or otherwise produce, transmit, distribute or store child pornography\
  \ or content otherwise depicting child exploitation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: by using the Wink App, you affirm that either you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/9count/eligibility/9count-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 9 Count's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer App
- Social Network
- Dating
- Mobile App
- Social Discovery
- Consumer Internet
- Media and Entertainment
---
