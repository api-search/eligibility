---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not remove or export from the United States or allow the export or re-export of the Service, Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations of the United States Department of Commerce
  entity_types:
  - text: Customer will use the Service only during this Agreement and solely for Customer’s own internal business purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or illegal activity
    text: Customer is using the Service for fraudulent or illegal activities
  - summary: Timesharing or service bureau
    text: use the Service or any Software for timesharing or service bureau purposes
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
name: Ediphi
provenance_date: '2026-11-09'
provider_name: Ediphi
provider_slug: ediphi
slug: ediphi-eligibility
source_date: '2026-11-09'
source_filename: ediphi-eligibility.yml
source_heading: Eligibility
source_page: https://www.ediphi.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ediphi\naid: ediphi\nurl: https://www.ediphi.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Service,\n    Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or\n    regulations of the United States Department of Commerce\nentity_types:\n- type: business\n  text: Customer will use the Service only during this Agreement and solely for Customer’s own internal business\n    purposes.\nrestricted_uses:\n- summary:\
  \ Fraudulent or illegal activity\n  text: Customer is using the Service for fraudulent or illegal activities\n- summary: Timesharing or service bureau\n  text: use the Service or any Software for timesharing or service bureau purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ediphi/eligibility/ediphi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Ediphi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Preconstruction
- Cost Estimating
- Construction Technology
- Estimating
- Cost Management
- Software-as-a-Service
---
