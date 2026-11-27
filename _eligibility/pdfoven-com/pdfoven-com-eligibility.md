---
api_specs:
- filename: pdfoven-com-render-api-openapi.yml
  format: yaml
  label: pdfoven-com Render API
  slug: pdfoven-com-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfoven-com/openapi/pdfoven-com-render-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to form a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent documents
    text: create or distribute unlawful, infringing, fraudulent or deceptive documents, including forged identity or financial documents
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
name: pdfoven-com
provenance_date: '2026-11-10'
provider_name: pdfoven-com
provider_slug: pdfoven-com
slug: pdfoven-com-eligibility
source_date: '2026-11-10'
source_filename: pdfoven-com-eligibility.yml
source_heading: Eligibility
source_page: https://pdfoven.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pdfoven-com\naid: pdfoven-com\nurl: https://pdfoven.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a binding contract.\nrestricted_uses:\n- summary: Unlawful or fraudulent documents\n  text: create or distribute unlawful, infringing, fraudulent or deceptive documents, including forged identity\n    or financial documents\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a\
  \ binding contract.\n"
source_yaml_url: https://artifacts.apis.io/pdfoven-com/eligibility/pdfoven-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from pdfoven-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Conversion
- Developers
---
