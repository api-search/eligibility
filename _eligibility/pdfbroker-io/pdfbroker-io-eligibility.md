---
api_specs:
- filename: pdfbroker-io-pdf-api-openapi.yml
  format: yaml
  label: pdfbroker-io PDF API
  slug: pdfbroker-io-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfbroker-io/openapi/pdfbroker-io-pdf-api-openapi.yml
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
  - summary: Illegal or harmful content
    text: Generate documents containing illegal, harmful, or offensive content
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
name: pdfbroker-io
provenance_date: '2026-11-10'
provider_name: pdfbroker-io
provider_slug: pdfbroker-io
slug: pdfbroker-io-eligibility
source_date: '2026-11-10'
source_filename: pdfbroker-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.pdfbroker.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pdfbroker-io\naid: pdfbroker-io\nurl: https://www.pdfbroker.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Generate documents containing illegal, harmful, or offensive content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pdfbroker-io/eligibility/pdfbroker-io-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from pdfbroker-io's own page on 2026-11-10.
synthetic: false
tags:
- PDF Generation
- REST API
- HTML to PDF
- PDF/A
- PDF/UA
- PDF Utilities
- XSL-FO
---
