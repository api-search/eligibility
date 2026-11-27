---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU ARE AT LEAST 18 YEARS OLD, (3) YOU HAVE READ AND UNDERSTAND THIS AGREEMENT
    type: individual
  - text: Healthcare professionals can provide their contact information to engage in communications with Impel.
    type: business
  minimum_age:
    text: 3.1.2. use the Site if you are under the age of eighteen (18) years old;
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful use
    text: use the Site for any illegal purpose, or in violation of any local, state, national, or international law
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
name: Impelpharma
provenance_date: '2026-11-09'
provider_name: Impelpharma
provider_slug: impelpharma
slug: impelpharma-eligibility
source_date: '2026-11-09'
source_filename: impelpharma-eligibility.yml
source_heading: Eligibility
source_page: https://impelpharma.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Impelpharma\naid: impelpharma\nurl: https://impelpharma.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU ARE AT LEAST 18 YEARS OLD, (3) YOU HAVE READ AND UNDERSTAND THIS AGREEMENT\n- type: business\n  text: Healthcare professionals can provide their contact information to engage in communications with Impel.\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: use the Site for any illegal purpose, or in violation of any local, state, national, or international law\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 3.1.2. use the Site if you are under the age of eighteen (18) years old;\n"
source_yaml_url: https://artifacts.apis.io/impelpharma/eligibility/impelpharma-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Impelpharma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmaceuticals
- Drug Delivery
- Healthcare
- Biotechnology
- Migraine
- CNS
- Nasal Delivery
- Life Sciences
---
