---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is intended for businesses operated by adults.
    type: business
  minimum_age:
    text: you are affirming that you are at least 18 years old or the legal age of majority in your state or province of residence (whichever is greater)
    value: '18'
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
name: Deskera
provenance_date: '2026-11-09'
provider_name: Deskera
provider_slug: deskera
slug: deskera-eligibility
source_date: '2026-11-09'
source_filename: deskera-eligibility.yml
source_heading: Eligibility
source_page: https://www.deskera.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deskera\naid: deskera\nurl: https://www.deskera.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Website is intended for businesses operated by adults.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are affirming that you are at least 18 years old or the legal age of majority in your state or province\n    of residence (whichever is greater)\n"
source_yaml_url: https://artifacts.apis.io/deskera/eligibility/deskera-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Deskera's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ERP
- Accounting
- CRM
- Human Resources
- Payroll
- Inventory
- Invoicing
- Small Business
- Software-as-a-Service
---
