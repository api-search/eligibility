---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Use violating law
    text: In any way that violates any applicable federal, state, local or international law or regulation
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
name: Rockerbox
provenance_date: '2026-11-10'
provider_name: Rockerbox
provider_slug: rockerbox
slug: rockerbox-eligibility
source_date: '2026-11-10'
source_filename: rockerbox-eligibility.yml
source_heading: Eligibility
source_page: https://www.rockerbox.com/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rockerbox\naid: rockerbox\nurl: https://www.rockerbox.com/website-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Use violating law\n  text: In any way that violates any applicable federal, state, local or international law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/rockerbox/eligibility/rockerbox-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Rockerbox's own page on 2026-11-10.
synthetic: false
tags:
- Marketing Attribution
- Multi-Touch Attribution
- Marketing Mix Modeling
- Incrementality Testing
- Media Spend
- Customer Journey
- Marketing Analytics
- Data Warehousing
- Conversion Tracking
- Webhook
- A2A
- Attribution
---
