---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A person signs in with an email address and a password, or with Google, and names an account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Screened content categories
    text: The default categories are minors, sexual content, violence, a named person, a brand mark and deception.
  - summary: Suspension on repeated refusals
    text: Repeated refusals inside a window suspend an account.
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
name: ugc-fans
provenance_date: '2026-11-10'
provider_name: ugc-fans
provider_slug: ugc-fans
slug: ugc-fans-eligibility
source_date: '2026-11-10'
source_filename: ugc-fans-eligibility.yml
source_heading: Eligibility
source_page: https://ugc.fans/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ugc-fans\naid: ugc-fans\nurl: https://ugc.fans/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A person signs in with an email address and a password, or with Google, and names an account.\nrestricted_uses:\n- summary: Screened content categories\n  text: The default categories are minors, sexual content, violence, a named person, a brand mark and deception.\n- summary: Suspension on repeated refusals\n  text: Repeated refusals inside a window suspend an account.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ugc-fans/eligibility/ugc-fans-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ugc-fans's own page on 2026-11-10.
synthetic: false
tags:
- Company
- UGC
- Content Platform
- Community
---
