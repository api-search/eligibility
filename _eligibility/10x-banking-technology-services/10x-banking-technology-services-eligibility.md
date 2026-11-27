---
api_specs:
- filename: overview
  format: yaml
  label: 10x Banking Platform API
  slug: 10x-banking-platform-api
  spec_type: Postman
  url: https://www.postman.com/openbanking10x/10x-banking-public-workspace/overview
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
  - summary: No production or regulated data
    text: Customer shall not upload, submit or process production data, live customer data, personal data, special category data, cardholder data, confidential regulatory data or other regulated information in the Evaluation Services
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
name: 10x Banking Technology Services
provenance_date: '2026-11-09'
provider_name: 10x Banking Technology Services
provider_slug: 10x-banking-technology-services
slug: 10x-banking-technology-services-eligibility
source_date: '2026-11-09'
source_filename: 10x-banking-technology-services-eligibility.yml
source_heading: Eligibility
source_page: https://www.10xbanking.com/platform-evaluation-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 10x Banking Technology Services\naid: 10x-banking-technology-services\nurl: https://www.10xbanking.com/platform-evaluation-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No production or regulated data\n  text: Customer shall not upload, submit or process production data, live customer data, personal data, special\n    category data, cardholder data, confidential regulatory data or other regulated information in the Evaluation\n    Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/10x-banking-technology-services/eligibility/10x-banking-technology-services-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from 10x Banking Technology Services's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- Core Banking
- Cloud-Native
- Banking as a Service
- Embedded Finance
- Payments
- Lending
- Deposits
- Cards
- Event-Driven
- United Kingdom
- Software-as-a-Service
- Fintech
---
