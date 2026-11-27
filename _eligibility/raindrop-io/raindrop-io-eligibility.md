---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: You must be 16 years or older to use this Service.
    value: '16'
  restricted_uses:
  - summary: Illegal use
    text: You may not use the Service for any illegal or unauthorized purpose.
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
name: Raindrop.io (bookmarks)
provenance_date: '2026-11-10'
provider_name: Raindrop.io (bookmarks)
provider_slug: raindrop-io
slug: raindrop-io-eligibility
source_date: '2026-11-10'
source_filename: raindrop-io-eligibility.yml
source_heading: Eligibility
source_page: https://help.raindrop.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Raindrop.io (bookmarks)\naid: raindrop-io\nurl: https://help.raindrop.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\n- summary: Illegal use\n  text: You may not use the Service for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be 16 years\
  \ or older to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/raindrop-io/eligibility/raindrop-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Raindrop.io (bookmarks)'s own page on 2026-11-10.
synthetic: false
tags:
- Bookmark
- Productivity
- Cloud
- Collaboration
---
