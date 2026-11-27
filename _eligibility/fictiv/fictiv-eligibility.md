---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU HAVE THE AUTHORITY TO ENTER INTO THIS AGREEMENT PERSONALLY OR ON BEHALF OF THE COMPANY YOU HAVE NAMED AS THE USER, AND TO BIND YOUR COMPANY TO THESE TERMS.
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FICTIV
    value: null
  restricted_uses:
  - summary: Illegal or weapons-related manufacturing
    text: use our Services for any illegal, illicit or unauthorized purpose, including to manufacture any products, components, goods or tools designed or intended for use in firearms, weapons
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
name: Fictiv
provenance_date: '2026-11-09'
provider_name: Fictiv
provider_slug: fictiv
slug: fictiv-eligibility
source_date: '2026-11-09'
source_filename: fictiv-eligibility.yml
source_heading: Eligibility
source_page: https://www.fictiv.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fictiv\naid: fictiv\nurl: https://www.fictiv.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: YOU HAVE THE AUTHORITY TO ENTER INTO THIS AGREEMENT PERSONALLY OR ON BEHALF OF THE COMPANY YOU HAVE NAMED\n    AS THE USER, AND TO BIND YOUR COMPANY TO THESE TERMS.\nrestricted_uses:\n- summary: Illegal or weapons-related manufacturing\n  text: use our Services for any illegal, illicit or unauthorized purpose, including to manufacture any products,\n    components, goods or tools designed or intended for use in firearms,\
  \ weapons\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FICTIV\n"
source_yaml_url: https://artifacts.apis.io/fictiv/eligibility/fictiv-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fictiv's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hardware
- Manufacturing
- Digital Manufacturing
- Supply Chain
- CNC Machining
- 3D Printing
- Injection Molding
- Sourcing
- Prototyping
---
