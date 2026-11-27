---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 1.14. “Supplier” means the person or entity to whom Antares issues the Purchase Order
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-controlled items
    text: Supplier shall not export, reexport, transfer, release, import, broker, or provide access to any controlled Goods, software, technology, technical data, Services, or Deliverables except as authorized by Applicable Law and the Purchase Order.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Supplier shall conduct appropriate restricted-party screening and immediately notify Antares if this representation becomes inaccurate.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Antares Nuclear
provenance_date: '2026-11-09'
provider_name: Antares Nuclear
provider_slug: antares-nuclear
slug: antares-nuclear-eligibility
source_date: '2026-11-09'
source_filename: antares-nuclear-eligibility.yml
source_heading: Eligibility
source_page: https://antaresindustries.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Antares Nuclear\naid: antares-nuclear\nurl: https://antaresindustries.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: 1.14. “Supplier” means the person or entity to whom Antares issues the Purchase Order\nrestricted_uses:\n- summary: Export-controlled items\n  text: Supplier shall not export, reexport, transfer, release, import, broker, or provide access to any controlled\n    Goods, software, technology, technical data, Services, or Deliverables except as authorized by Applicable Law\n    and\
  \ the Purchase Order.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Supplier shall conduct appropriate restricted-party screening and immediately notify Antares if this representation\n    becomes inaccurate.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/antares-nuclear/eligibility/antares-nuclear-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Antares Nuclear's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Nuclear
- Energy
- Microreactor
- Defense
---
