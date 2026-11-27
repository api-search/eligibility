---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Prohibited uses
    text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose'
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We reserve the right to refuse service to anyone for any reason at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blox
provenance_date: '2026-11-09'
provider_name: Blox
provider_slug: blox
slug: blox-eligibility
source_date: '2026-11-09'
source_filename: blox-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloxbuilt.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blox\naid: blox\nurl: https://www.bloxbuilt.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least the age of majority in your state or province of residence\nrestricted_uses:\n- summary: Prohibited uses\n  text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: We reserve the right to refuse service to anyone for any reason at any time.\nminimum_age:\n  value: age of majority\n  text:\
  \ you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/blox/eligibility/blox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Blox's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Modular Construction
- Prefabrication
- Manufacturing
- Healthcare Facilities
- Architecture
- Building Technology
---
