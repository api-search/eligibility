---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Services are available to authorized representatives of legal entities
    type: business
  - text: individuals who are either (i) at least 18 years old to register for Premium Accounts or license Visual Content through 500px, or (ii) at least 14 years old, and who are authorized to access the Site by a parent or legal guardian
    type: individual
  minimum_age:
    text: at least 14 years old, and who are authorized to access the Site by a parent or legal guardian
    value: '14'
  restricted_uses:
  - summary: No AI-generated content uploads
    text: You may not upload, store, publish, transmit, or otherwise make available any Artificial Intelligence Generated Content (AIGC) through the Services.
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
name: 500px
provenance_date: '2026-11-09'
provider_name: 500px
provider_slug: 500px
slug: 500px-eligibility
source_date: '2026-11-09'
source_filename: 500px-eligibility.yml
source_heading: Eligibility
source_page: https://500px.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 500px\naid: 500px\nurl: https://500px.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Services are available to authorized representatives of legal entities\n- type: individual\n  text: individuals who are either (i) at least 18 years old to register for Premium Accounts or license Visual\n    Content through 500px, or (ii) at least 14 years old, and who are authorized to access the Site by a parent\n    or legal guardian\nrestricted_uses:\n- summary: No AI-generated content uploads\n  text: You may not upload, store, publish,\
  \ transmit, or otherwise make available any Artificial Intelligence Generated\n    Content (AIGC) through the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: at least 14 years old, and who are authorized to access the Site by a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/500px/eligibility/500px-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 500px's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Photography
- Stock Photos
- Image Licensing
- Community
- Social Network
- Media
- Content
---
