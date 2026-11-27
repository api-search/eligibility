---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the undersigned software developer (“Developer”)
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only for Common Clients
    text: (a.i.1.l) use any API or Interface, or Information transmitted through the API or Interface, for any individual or entity that is not a Common Client of Developer and Entrata
  - summary: Export restrictions
    text: (a.i.1.f) access or use any API or Interface, or transmit any data through any API or Interface, in violation of any U.S. export embargo, prohibition or restriction
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
name: Entrata
provenance_date: '2026-11-09'
provider_name: Entrata
provider_slug: entrata
slug: entrata-eligibility
source_date: '2026-11-09'
source_filename: entrata-eligibility.yml
source_heading: Eligibility
source_page: https://commoncdn.entrata.com/legal/api/api_document_agreement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Entrata\naid: entrata\nurl: https://commoncdn.entrata.com/legal/api/api_document_agreement.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: the undersigned software developer (“Developer”)\nrestricted_uses:\n- summary: Only for Common Clients\n  text: (a.i.1.l) use any API or Interface, or Information transmitted through the API or Interface, for any individual\n    or entity that is not a Common Client of Developer and Entrata\n- summary: Export restrictions\n  text: (a.i.1.f) access or use any API or Interface, or transmit any\
  \ data through any API or Interface, in violation\n    of any U.S. export embargo, prohibition or restriction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/entrata/eligibility/entrata-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Entrata's own page on 2026-11-09.
synthetic: false
tags:
- Property Management
- Multifamily Housing
- Real Estate
- Resident Management
- Leasing
- Maintenance
- Payments
- Accounting
---
