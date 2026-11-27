---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Children under the age of eighteen (18) years old are prohibited from using the Services.
    type: individual
  minimum_age:
    text: the Services are not intended for use by children under the age of eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: Andros grants you a limited, revocable, non-exclusive, and non-transferable right to access and otherwise use the Services for your non-commercial purposes.
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
name: Andros
provenance_date: '2026-11-09'
provider_name: Andros
provider_slug: andros
slug: andros-eligibility
source_date: '2026-11-09'
source_filename: andros-eligibility.yml
source_heading: Eligibility
source_page: https://andros.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Andros\naid: andros\nurl: https://andros.co/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Children under the age of eighteen (18) years old are prohibited from using the Services.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: Andros grants you a limited, revocable, non-exclusive, and non-transferable right to access and otherwise\n    use the Services for your non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the\
  \ Services are not intended for use by children under the age of eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/andros/eligibility/andros-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Andros's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Provider Network
- Credentialing
- Data Management
---
