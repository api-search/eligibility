---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representation that any of the materials or the services to which you have been given access are available or appropriate for use in other locations.
  entity_types:
  - text: Certificates may only be obtained and held by individuals.
    type: individual
  minimum_age:
    text: YOU AGREE THAT BY USING THE SERVICE YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Violation of security features
    text: You are prohibited from violating or attempting to violate any security features of the Site or Service
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
name: Sepasoft
provenance_date: '2026-11-10'
provider_name: Sepasoft
provider_slug: sepasoft
slug: sepasoft-eligibility
source_date: '2026-11-10'
source_filename: sepasoft-eligibility.yml
source_heading: Eligibility
source_page: https://www.sepasoft.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sepasoft\naid: sepasoft\nurl: https://www.sepasoft.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representation that any of the materials or the services to which you have been given access\n    are available or appropriate for use in other locations.\nentity_types:\n- type: individual\n  text: Certificates may only be obtained and held by individuals.\nrestricted_uses:\n- summary: Violation of security features\n  text: You are prohibited from violating or attempting to violate any security features of the Site or Service\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU AGREE THAT BY USING THE SERVICE YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/sepasoft/eligibility/sepasoft-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sepasoft's own page on 2026-11-10.
synthetic: false
tags:
- Manufacturing
- Manufacturing Execution System
- Industrial Automation
- OEE
- Track and Trace
- Batch Processing
- Statistical Process Control
- ERP Integration
- ISA-95
- Ignition
---
