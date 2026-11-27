---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may be using our Sites and/or Interactive and Digital Services on behalf of a company or other legal entity.
    type: business
  minimum_age:
    text: you are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Not a competitor
    text: you are not a competitor of Electra and are not using the Interactive and Digital Services for reasons that are in competition with Electra
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
name: Gresham Technologies
provenance_date: '2026-11-09'
provider_name: Gresham Technologies
provider_slug: electrainfo
slug: electrainfo-eligibility
source_date: '2026-11-09'
source_filename: electrainfo-eligibility.yml
source_heading: Eligibility
source_page: https://dashboard.electrainfo.com/terms-of-use.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gresham Technologies\naid: electrainfo\nurl: https://dashboard.electrainfo.com/terms-of-use.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may be using our Sites and/or Interactive and Digital Services on behalf of a company or other legal\n    entity.\nrestricted_uses:\n- summary: Not a competitor\n  text: you are not a competitor of Electra and are not using the Interactive and Digital Services for reasons that\n    are in competition with Electra\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '13'\n  text: you are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/electrainfo/eligibility/electrainfo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Gresham Technologies's own page on 2026-11-09.
synthetic: false
tags:
- Enterprise Data Management
- Reconciliation
- Regulatory Reporting
- Data Services
- Financial Services
- ESG Data
- Trading Data
---
