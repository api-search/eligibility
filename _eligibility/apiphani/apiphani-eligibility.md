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
  - summary: Illegal spam
    text: You are strictly prohibited from using the Website or any of the Company’s Services for illegal spam activities, including gathering email addresses and personal information from others or sending any mass commercial emails.
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
name: Apiphani
provenance_date: '2026-11-09'
provider_name: Apiphani
provider_slug: apiphani
slug: apiphani-eligibility
source_date: '2026-11-09'
source_filename: apiphani-eligibility.yml
source_heading: Eligibility
source_page: https://www.apiphani.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apiphani\naid: apiphani\nurl: https://www.apiphani.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal spam\n  text: You are strictly prohibited from using the Website or any of the Company’s Services for illegal spam activities,\n    including gathering email addresses and personal information from others or sending any mass commercial emails.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apiphani/eligibility/apiphani-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Apiphani's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Managed Service
- SAP
- Application Management
- Cloud
- Observability
- AIOps
- Enterprise Software
- Security
---
