---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY, AND CAPACITY TO BIND SUCH ENTITY TO THIS AGREEMENT.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls
    text: you must not use or otherwise export or re-export any Site or Site Materials except as authorized by Export Control Laws.
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
name: GrabCAD
provenance_date: '2026-11-09'
provider_name: GrabCAD
provider_slug: grabcad
slug: grabcad-eligibility
source_date: '2026-11-09'
source_filename: grabcad-eligibility.yml
source_heading: Eligibility
source_page: https://grabcad.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GrabCAD\naid: grabcad\nurl: https://grabcad.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY,\n    AND CAPACITY TO BIND SUCH ENTITY TO THIS AGREEMENT.\nrestricted_uses:\n- summary: Export controls\n  text: you must not use or otherwise export or re-export any Site or Site Materials except as authorized by Export\n    Control Laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/grabcad/eligibility/grabcad-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from GrabCAD's own page on 2026-11-09.
synthetic: false
tags:
- Company
- B2B
- 3D Printing
- CAD
- Manufacturing
- Hardware
- Developer SDK
---
