---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any person having the full legal capacity to be bound by these General Terms and Conditions.
    type: individual
  - text: Any entity acting through a person having full legal capacity to contract for and on behalf of the entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Professional use only
    text: The Application and the Services are designed and meant for professional use, so that they are intended exclusively for professionals within their activity.
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
name: Palette
provenance_date: '2026-11-10'
provider_name: Palette
provider_slug: palette
slug: palette-eligibility
source_date: '2026-11-10'
source_filename: palette-eligibility.yml
source_heading: Eligibility
source_page: https://www.palettehq.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Palette\naid: palette\nurl: https://www.palettehq.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any person having the full legal capacity to be bound by these General Terms and Conditions.\n- type: business\n  text: Any entity acting through a person having full legal capacity to contract for and on behalf of the entity.\nrestricted_uses:\n- summary: Professional use only\n  text: The Application and the Services are designed and meant for professional use, so that they are intended\n    exclusively for professionals\
  \ within their activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/palette/eligibility/palette-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Palette's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Apps
- Sales Compensation
- Commission Management
- Revenue Operations
- Sales
- FinOps
- Software-as-a-Service
---
