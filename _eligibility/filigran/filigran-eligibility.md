---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity identified as the "Customer" in the applicable Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Trial non-production only
    text: the Customer agrees to use the Trial solely in a non-production environment.
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
name: Filigran
provenance_date: '2026-11-09'
provider_name: Filigran
provider_slug: filigran
slug: filigran-eligibility
source_date: '2026-11-09'
source_filename: filigran-eligibility.yml
source_heading: Eligibility
source_page: https://filigran.io/mssa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Filigran\naid: filigran\nurl: https://filigran.io/mssa\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity identified as the \"Customer\" in the applicable Order Form\nrestricted_uses:\n- summary: Trial non-production only\n  text: the Customer agrees to use the Trial solely in a non-production environment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/filigran/eligibility/filigran-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Filigran's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Threat Intelligence
- OpenCTI
- OpenAEV
- STIX
- GraphQL
- Breach and Attack Simulation
- Open Source
- Security
---
