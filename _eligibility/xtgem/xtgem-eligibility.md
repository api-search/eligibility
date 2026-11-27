---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only persons who are over 14 years old have a right to use the services provided by XTGEM
    type: individual
  minimum_age:
    text: Only persons who are over 14 years old have a right to use the services provided by XTGEM
    value: '14'
  restricted_uses:
  - summary: Content that may harm minors limited to adults
    text: the services and the data provided by XTGEM, which may negatively affect minors, can only be used by the persons who are over 18 years old.
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
name: XtGem
provenance_date: '2026-11-10'
provider_name: XtGem
provider_slug: xtgem
slug: xtgem-eligibility
source_date: '2026-11-10'
source_filename: xtgem-eligibility.yml
source_heading: Eligibility
source_page: https://xtgem.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: XtGem\naid: xtgem\nurl: https://xtgem.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only persons who are over 14 years old have a right to use the services provided by XTGEM\nrestricted_uses:\n- summary: Content that may harm minors limited to adults\n  text: the services and the data provided by XTGEM, which may negatively affect minors, can only be used by the\n    persons who are over 18 years old.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: Only\
  \ persons who are over 14 years old have a right to use the services provided by XTGEM\n"
source_yaml_url: https://artifacts.apis.io/xtgem/eligibility/xtgem-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from XtGem's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Website Builder
- Mobile
- Hosting
- Templates
- No-Code
- Lithuania
---
