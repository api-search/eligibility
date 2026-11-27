---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: solicits personal information from anyone under 18;
    value: null
  restricted_uses:
  - summary: Commercial use restricted
    text: may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by Diigo.com
  - summary: Lawful use only
    text: By using the Services, you represent and warrant that your use of the Services does not violate any applicable law or regulation.
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
name: Diigo
provenance_date: '2026-11-09'
provider_name: Diigo
provider_slug: diigo
slug: diigo-eligibility
source_date: '2026-11-09'
source_filename: diigo-eligibility.yml
source_heading: Eligibility
source_page: https://www.diigo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diigo\naid: diigo\nurl: https://www.diigo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial use restricted\n  text: may not be used in connection with any commercial endeavors except those that are specifically endorsed\n    or approved by Diigo.com\n- summary: Lawful use only\n  text: By using the Services, you represent and warrant that your use of the Services does not violate any applicable\n    law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: solicits personal information from anyone under 18;\n"
source_yaml_url: https://artifacts.apis.io/diigo/eligibility/diigo-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Diigo's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
