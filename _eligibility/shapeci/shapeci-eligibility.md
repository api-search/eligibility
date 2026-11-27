---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content
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
name: ShapeCI
provenance_date: '2026-11-10'
provider_name: ShapeCI
provider_slug: shapeci
slug: shapeci-eligibility
source_date: '2026-11-10'
source_filename: shapeci-eligibility.yml
source_heading: Eligibility
source_page: https://www.shape.ci/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShapeCI\naid: shapeci\nurl: https://www.shape.ci/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms\
  \ if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/shapeci/eligibility/shapeci-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ShapeCI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hardware
- Version Control
- PDM
- Product Data Management
- CAD
- Manufacturing
- Engineering
- Collaboration
- Industrial
- Developer Tools
---
