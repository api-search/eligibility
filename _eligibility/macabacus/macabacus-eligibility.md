---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “User” means a single employee or individual engaged in the Use of the Software.
    type: individual
  - text: “Licensee” means You or Your Company, unless otherwise indicated.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Trademark use limited
    text: Trademarks can only be used to identify printed output produced by the Software
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
name: Macabacus
provenance_date: '2026-11-10'
provider_name: Macabacus
provider_slug: macabacus
slug: macabacus-eligibility
source_date: '2026-11-10'
source_filename: macabacus-eligibility.yml
source_heading: Eligibility
source_page: https://macabacus.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Macabacus\naid: macabacus\nurl: https://macabacus.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “User” means a single employee or individual engaged in the Use of the Software.\n- type: business\n  text: “Licensee” means You or Your Company, unless otherwise indicated.\nrestricted_uses:\n- summary: Trademark use limited\n  text: Trademarks can only be used to identify printed output produced by the Software\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/macabacus/eligibility/macabacus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Macabacus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Excel
- PowerPoint
- Word
- Modeling
---
