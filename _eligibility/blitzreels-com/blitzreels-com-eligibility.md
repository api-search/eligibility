---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for businesses and creators producing short-form content.
    type: business
  minimum_age:
    text: be at least 13 years old to use our service.
    value: '13'
  restricted_uses:
  - summary: AI features minimum age 18 where required
    text: AI generation features are subject to the selected provider's eligibility rules, including a minimum age of 18 where required.
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
name: BlitzReels
provenance_date: '2026-11-09'
provider_name: BlitzReels
provider_slug: blitzreels-com
slug: blitzreels-com-eligibility
source_date: '2026-11-09'
source_filename: blitzreels-com-eligibility.yml
source_heading: Eligibility
source_page: https://blitzreels.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlitzReels\naid: blitzreels-com\nurl: https://blitzreels.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: for businesses and creators producing short-form content.\nrestricted_uses:\n- summary: AI features minimum age 18 where required\n  text: AI generation features are subject to the selected provider's eligibility rules, including a minimum age\n    of 18 where required.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: be at least 13 years old to use our\
  \ service.\n"
source_yaml_url: https://artifacts.apis.io/blitzreels-com/eligibility/blitzreels-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BlitzReels's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video
- Social Media
- Content Creation
- Automation
---
