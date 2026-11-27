---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be old enough to form a binding contract in your jurisdiction to use the Service.
    value: null
  restricted_uses:
  - summary: Exploitation of minors and unlawful or hateful content
    text: Create material depicting the exploitation of minors, or unlawful, harassing or hateful content.
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
name: PixelDrive
provenance_date: '2026-11-10'
provider_name: PixelDrive
provider_slug: pixeldrive-pro
slug: pixeldrive-pro-eligibility
source_date: '2026-11-10'
source_filename: pixeldrive-pro-eligibility.yml
source_heading: Eligibility
source_page: https://pixeldrive.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PixelDrive\naid: pixeldrive-pro\nurl: https://pixeldrive.pro/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Exploitation of minors and unlawful or hateful content\n  text: Create material depicting the exploitation of minors, or unlawful, harassing or hateful content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to form a binding contract in your jurisdiction to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/pixeldrive-pro/eligibility/pixeldrive-pro-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from PixelDrive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Image Generation
- Bulk Rendering
- Marketing
---
