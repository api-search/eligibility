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
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To verify the Customer's identity and creditworthiness, the Provider is entitled to obtain information and, if necessary, credit reports from SCHUFA Holding AG
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lanes & Planes
provenance_date: '2026-11-09'
provider_name: Lanes & Planes
provider_slug: lanes-and-planes
slug: lanes-and-planes-eligibility
source_date: '2026-11-09'
source_filename: lanes-and-planes-eligibility.yml
source_heading: Eligibility
source_page: https://www.lanes-planes.com/en/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lanes & Planes\naid: lanes-and-planes\nurl: https://www.lanes-planes.com/en/agb/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To verify the Customer's identity and creditworthiness, the Provider is entitled to obtain information and,\n    if necessary, credit reports from SCHUFA Holding AG\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lanes-and-planes/eligibility/lanes-and-planes-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Lanes & Planes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Business Travel
- Travel Management
- Expense Management
- Spend Management
- Finance
- Accounting
- ERP Integration
- HRIS
- Software-as-a-Service
- Germany
- Europe
---
