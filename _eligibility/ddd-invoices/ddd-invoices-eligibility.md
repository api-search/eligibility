---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The "Client" is an individual or legal entity that, for the purpose of optimized exchange of e-documents, wants to establish Integration with the Platform.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Peppol blocking
    text: A user may be blocked from the Peppol Network in case of fraud, spam or other criminal acts.
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
name: DDD Invoices
provenance_date: '2026-11-09'
provider_name: DDD Invoices
provider_slug: ddd-invoices
slug: ddd-invoices-eligibility
source_date: '2026-11-09'
source_filename: ddd-invoices-eligibility.yml
source_heading: Eligibility
source_page: https://dddinvoices.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DDD Invoices\naid: ddd-invoices\nurl: https://dddinvoices.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The \"Client\" is an individual or legal entity that, for the purpose of optimized exchange of e-documents,\n    wants to establish Integration with the Platform.\nrestricted_uses:\n- summary: Peppol blocking\n  text: A user may be blocked from the Peppol Network in case of fraud, spam or other criminal acts.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ddd-invoices/eligibility/ddd-invoices-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from DDD Invoices's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Invoicing
- Fiscalization
- Tax Compliance
- Real-Time Reporting
- Peppol
- Invoicing
---
