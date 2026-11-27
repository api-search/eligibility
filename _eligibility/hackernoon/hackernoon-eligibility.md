---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To access or use the Site, you must be 13 years of age or older, and have the requisite power and authority to enter into these User Terms.
    type: individual
  minimum_age:
    text: To access or use the Site, you must be 13 years of age or older
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
name: Hackernoon
provenance_date: '2026-11-09'
provider_name: Hackernoon
provider_slug: hackernoon
slug: hackernoon-eligibility
source_date: '2026-11-09'
source_filename: hackernoon-eligibility.yml
source_heading: Eligibility
source_page: https://hackernoon.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hackernoon\naid: hackernoon\nurl: https://hackernoon.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To access or use the Site, you must be 13 years of age or older, and have the requisite power and authority\n    to enter into these User Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To access or use the Site, you must be 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/hackernoon/eligibility/hackernoon-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Hackernoon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Publishing
- Content
- Technology
- Developer Community
- AI Licensing
- Open Source
- Syndication
- Content Licensing
---
