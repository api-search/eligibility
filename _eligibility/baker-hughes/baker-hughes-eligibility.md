---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are over the age of legal majority and able to form a legally binding agreement under applicable law
    type: individual
  minimum_age:
    text: you are over the age of legal majority
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: not to export or re-export the Content (including any software or the Services) to countries or persons prohibited under the United States or other applicable export control laws or regulations.
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
name: Baker Hughes
provenance_date: '2026-11-09'
provider_name: Baker Hughes
provider_slug: baker-hughes
slug: baker-hughes-eligibility
source_date: '2026-11-09'
source_filename: baker-hughes-eligibility.yml
source_heading: Eligibility
source_page: https://www.bakerhughes.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baker Hughes\naid: baker-hughes\nurl: https://www.bakerhughes.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are over the age of legal majority and able to form a legally binding agreement under applicable law\nrestricted_uses:\n- summary: Export control compliance\n  text: not to export or re-export the Content (including any software or the Services) to countries or persons\n    prohibited under the United States or other applicable export control laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: you are over the age of legal majority\n"
source_yaml_url: https://artifacts.apis.io/baker-hughes/eligibility/baker-hughes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Baker Hughes's own page on 2026-11-09.
synthetic: false
tags:
- Energy Technology
- Industrial IoT
- Oil and Gas
- Asset Performance Management
- Digital Energy
- Fortune 500
---
