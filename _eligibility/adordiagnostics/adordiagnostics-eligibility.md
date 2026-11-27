---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Registration is intended for professional users - healthcare institutions, laboratories, distributors, and their authorised staff
    type: business
  - text: individuals of at least 18 years of age acting on behalf of such organisations
    type: individual
  minimum_age:
    text: individuals of at least 18 years of age acting on behalf of such organisations
    value: '18'
  restricted_uses:
  - summary: Professional use only
    text: The Site presents the NATlab system and associated in vitro diagnostic (IVD) syndromic panels intended for professional use only.
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
name: ADOR Diagnostics
provenance_date: '2026-11-09'
provider_name: ADOR Diagnostics
provider_slug: adordiagnostics
slug: adordiagnostics-eligibility
source_date: '2026-11-09'
source_filename: adordiagnostics-eligibility.yml
source_heading: Eligibility
source_page: https://www.adordx.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ADOR Diagnostics\naid: adordiagnostics\nurl: https://www.adordx.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Registration is intended for professional users - healthcare institutions, laboratories, distributors, and\n    their authorised staff\n- type: individual\n  text: individuals of at least 18 years of age acting on behalf of such organisations\nrestricted_uses:\n- summary: Professional use only\n  text: The Site presents the NATlab system and associated in vitro diagnostic (IVD) syndromic panels intended\
  \ for\n    professional use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: individuals of at least 18 years of age acting on behalf of such organisations\n"
source_yaml_url: https://artifacts.apis.io/adordiagnostics/eligibility/adordiagnostics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ADOR Diagnostics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Devices
- In Vitro Diagnostics
- Molecular Diagnostics
- Infectious Disease
- Point of Care
- Laboratory
- Life Sciences
- MCP
---
