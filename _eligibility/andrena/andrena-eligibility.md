---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons or jurisdictions
    text: Customer shall not use the Services in violation of applicable export control laws, for prohibited end uses, for sanctioned persons or jurisdictions, or in violation of trade restrictions, sanctions laws, or telecommunications restrictions.
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
name: Andrena
provenance_date: '2026-11-09'
provider_name: Andrena
provider_slug: andrena
slug: andrena-eligibility
source_date: '2026-11-09'
source_filename: andrena-eligibility.yml
source_heading: Eligibility
source_page: https://andrena.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Andrena\naid: andrena\nurl: https://andrena.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned persons or jurisdictions\n  text: Customer shall not use the Services in violation of applicable export control laws, for prohibited end uses,\n    for sanctioned persons or jurisdictions, or in violation of trade restrictions, sanctions laws, or telecommunications\n    restrictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/andrena/eligibility/andrena-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Andrena's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Internet
- Wireless
- Broadband
- Residential
- Business
---
