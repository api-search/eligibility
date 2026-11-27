---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer is at least 18 years old and has the legal capacity to be bound by this Agreement
    type: individual
  - text: entering into this Agreement on behalf of and binding a third-party, if so applicable
    type: business
  minimum_age:
    text: Customer is at least 18 years old and has the legal capacity to be bound by this Agreement
    value: '18'
  restricted_uses:
  - summary: Competing or derivative products
    text: to develop or market any product, software or service that is functionally similar to or derivative of the Service
  - summary: Protected health information
    text: upload or otherwise make available to IOpipe any information that constitutes protected health information subject to the Health Insurance Portability and Accountability Act
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer will provide IOpipe with any information, records, or materials that we request to verify Customer’s compliance with the eligibility requirements set forth above
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: IOpipe
provenance_date: '2026-11-09'
provider_name: IOpipe
provider_slug: iopipe
slug: iopipe-eligibility
source_date: '2026-11-09'
source_filename: iopipe-eligibility.yml
source_heading: Eligibility
source_page: https://www.iopipe.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IOpipe\naid: iopipe\nurl: https://www.iopipe.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Customer is at least 18 years old and has the legal capacity to be bound by this Agreement\n- type: business\n  text: entering into this Agreement on behalf of and binding a third-party, if so applicable\nrestricted_uses:\n- summary: Competing or derivative products\n  text: to develop or market any product, software or service that is functionally similar to or derivative of the\n    Service\n- summary: Protected health information\n\
  \  text: upload or otherwise make available to IOpipe any information that constitutes protected health information\n    subject to the Health Insurance Portability and Accountability Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer will provide IOpipe with any information, records, or materials that we request to verify Customer’s\n    compliance with the eligibility requirements set forth above\nminimum_age:\n  value: '18'\n  text: Customer is at least 18 years old and has the legal capacity to be bound by this Agreement\n"
source_yaml_url: https://artifacts.apis.io/iopipe/eligibility/iopipe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from IOpipe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Monitoring
- Observability
- Serverless
- Amazon Web Services
---
