---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE EXECUTING THIS LICENSE ON BEHALF OF A COMPANY, YOU REPRESENT THAT YOU ARE AUTHORIZED TO BIND THE COMPANY.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: Licensee shall comply with all such regulations and agrees to obtain all necessary licenses to export, re-export, or import the Products
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
name: Dyndrite
provenance_date: '2026-11-09'
provider_name: Dyndrite
provider_slug: dyndrite
slug: dyndrite-eligibility
source_date: '2026-11-09'
source_filename: dyndrite-eligibility.yml
source_heading: Eligibility
source_page: https://www.dyndrite.com/privacy-and-terms/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dyndrite\naid: dyndrite\nurl: https://www.dyndrite.com/privacy-and-terms/eula\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE EXECUTING THIS LICENSE ON BEHALF OF A COMPANY, YOU REPRESENT THAT YOU ARE AUTHORIZED TO BIND\n    THE COMPANY.\nrestricted_uses:\n- summary: Export control compliance\n  text: Licensee shall comply with all such regulations and agrees to obtain all necessary licenses to export, re-export,\n    or import the Products\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dyndrite/eligibility/dyndrite-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dyndrite's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- 3D Printing
- Digital Manufacturing
- Manufacturing Automation
- GPU Computing
- Toolpathing
---
