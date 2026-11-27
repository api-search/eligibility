---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACCESSING AND USING THE SITES ON BEHALF OF A COMPANY (SUCH AS YOUR EMPLOYER) OR OTHER LEGAL ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND THAT ENTITY TO THESE TERMS.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You shall not, without prior U.S. government authorization, export, re-export, or transfer the Sites, the Site Materials or any other Last Energy products, services or technology, either directly or indirectly, in violation of applicable laws and regulations.
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
name: Last Energy
provenance_date: '2026-11-09'
provider_name: Last Energy
provider_slug: last-energy
slug: last-energy-eligibility
source_date: '2026-11-09'
source_filename: last-energy-eligibility.yml
source_heading: Eligibility
source_page: https://www.lastenergy.com/privacy-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Last Energy\naid: last-energy\nurl: https://www.lastenergy.com/privacy-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACCESSING AND USING THE SITES ON BEHALF OF A COMPANY (SUCH AS YOUR EMPLOYER) OR OTHER LEGAL ENTITY,\n    YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND THAT ENTITY TO THESE TERMS.\nrestricted_uses:\n- summary: Export restrictions\n  text: You shall not, without prior U.S. government authorization, export, re-export, or transfer the Sites, the\n    Site Materials or any other Last Energy\
  \ products, services or technology, either directly or indirectly, in\n    violation of applicable laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/last-energy/eligibility/last-energy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Last Energy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Nuclear Energy
- Small Modular Reactor
- Electricity
- Power Generation
- Data Center
- Industrial
- Clean Energy
- Infrastructure
---
