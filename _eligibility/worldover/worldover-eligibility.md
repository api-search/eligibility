---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Customer: means the person purchasing the Services (as set out in the Order Form).'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Import/export compliance
    text: use the Services and/or Documentation and/or Deliverables in a way which would breach any import, export or customs rules or regulations
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
name: Worldover
provenance_date: '2026-11-10'
provider_name: Worldover
provider_slug: worldover
slug: worldover-eligibility
source_date: '2026-11-10'
source_filename: worldover-eligibility.yml
source_heading: Eligibility
source_page: https://worldover.io/legal/worldover-terms-of-use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Worldover\naid: worldover\nurl: https://worldover.io/legal/worldover-terms-of-use.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Customer: means the person purchasing the Services (as set out in the Order Form).'\nrestricted_uses:\n- summary: Import/export compliance\n  text: use the Services and/or Documentation and/or Deliverables in a way which would breach any import, export\n    or customs rules or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n \
  \ text: null\n"
source_yaml_url: https://artifacts.apis.io/worldover/eligibility/worldover-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Worldover's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Applications
- Cosmetics
- Chemicals
- Regulatory Compliance
- Quality Management
- ERP
- Artificial Intelligence
---
