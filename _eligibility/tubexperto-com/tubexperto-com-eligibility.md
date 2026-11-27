---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if the user acts as a business or professional, the parties submit to the Courts and Tribunals of Málaga (Spain)
    type: business
  - text: If the user is a consumer, the competent courts are those determined by the applicable mandatory law
    type: individual
  minimum_age:
    text: null
    value: null
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
name: tubexperto-com
provenance_date: '2026-11-10'
provider_name: tubexperto-com
provider_slug: tubexperto-com
slug: tubexperto-com-eligibility
source_date: '2026-11-10'
source_filename: tubexperto-com-eligibility.yml
source_heading: Eligibility
source_page: https://tubexperto.com/en/legal-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tubexperto-com\naid: tubexperto-com\nurl: https://tubexperto.com/en/legal-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if the user acts as a business or professional, the parties submit to the Courts and Tribunals of Málaga\n    (Spain)\n- type: individual\n  text: If the user is a consumer, the competent courts are those determined by the applicable mandatory law\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tubexperto-com/eligibility/tubexperto-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from tubexperto-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Video
- YouTube
- Analytics
- Content
---
