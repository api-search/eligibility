---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “You” or “Journalist” shall refer to Egab’s journalists registered over its website.
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use our Services, you must onboard over Egab and provide to us the required information details
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Egab
provenance_date: '2026-11-09'
provider_name: Egab
provider_slug: egab
slug: egab-eligibility
source_date: '2026-11-09'
source_filename: egab-eligibility.yml
source_heading: Eligibility
source_page: https://www.egab.co/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Egab\naid: egab\nurl: https://www.egab.co/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “You” or “Journalist” shall refer to Egab’s journalists registered over its website.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use our Services, you must onboard over Egab and provide to us the required information details\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/egab/eligibility/egab-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Egab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Journalism
- Media
- News
- Solutions Journalism
- Global South
- Publishing
- Newsrooms
- Content Marketplace
---
