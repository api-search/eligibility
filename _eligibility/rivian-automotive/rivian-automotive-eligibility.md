---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU MAY NOT ORDER OR OBTAIN A RIVIAN VEHICLE OR PRODUCTS OR SERVICES FROM RIVIAN IF YOU (A) DO NOT AGREE TO THESE RIVIAN TERMS, (B) ARE NOT THE OLDER OF (i) AT LEAST 18 YEARS OF AGE
    type: individual
  minimum_age:
    text: ARE NOT THE OLDER OF (i) AT LEAST 18 YEARS OF AGE OR (ii) LEGAL AGE TO FORM A BINDING CONTRACT WITH RIVIAN
    value: '18'
  restricted_uses:
  - summary: Safety-critical and hazardous uses of apps
    text: use the Rivian Apps in, or in association with, the design, construction, maintenance, or operation of any hazardous environments or systems
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
name: Rivian Automotive
provenance_date: '2026-11-10'
provider_name: Rivian Automotive
provider_slug: rivian-automotive
slug: rivian-automotive-eligibility
source_date: '2026-11-10'
source_filename: rivian-automotive-eligibility.yml
source_heading: Eligibility
source_page: https://rivian.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rivian Automotive\naid: rivian-automotive\nurl: https://rivian.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU MAY NOT ORDER OR OBTAIN A RIVIAN VEHICLE OR PRODUCTS OR SERVICES FROM RIVIAN IF YOU (A) DO NOT AGREE\n    TO THESE RIVIAN TERMS, (B) ARE NOT THE OLDER OF (i) AT LEAST 18 YEARS OF AGE\nrestricted_uses:\n- summary: Safety-critical and hazardous uses of apps\n  text: use the Rivian Apps in, or in association with, the design, construction, maintenance, or operation of any\n    hazardous\
  \ environments or systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: ARE NOT THE OLDER OF (i) AT LEAST 18 YEARS OF AGE OR (ii) LEGAL AGE TO FORM A BINDING CONTRACT WITH RIVIAN\n"
source_yaml_url: https://artifacts.apis.io/rivian-automotive/eligibility/rivian-automotive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rivian Automotive's own page on 2026-11-10.
synthetic: false
tags:
- Automotive
- Electric Vehicles
- Connected Vehicles
- Manufacturing
- Fortune 500
---
