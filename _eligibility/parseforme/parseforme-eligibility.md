---
api_specs:
- filename: parseforme-webhooks-api-openapi.yml
  format: yaml
  label: ParseForMe Webhooks API
  slug: parseforme-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-webhooks-api-openapi.yml
- filename: parseforme-document-types-api-openapi.yml
  format: yaml
  label: ParseForMe Document Types API
  slug: parseforme-document-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-document-types-api-openapi.yml
- filename: parseforme-documents-api-openapi.yml
  format: yaml
  label: ParseForMe Documents API
  slug: parseforme-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-documents-api-openapi.yml
- filename: parseforme-me-api-openapi.yml
  format: yaml
  label: ParseForMe Me API
  slug: parseforme-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-me-api-openapi.yml
- filename: parseforme-meta-api-openapi.yml
  format: yaml
  label: ParseForMe Meta API
  slug: parseforme-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-meta-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful content
    text: You must not upload unlawful content
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
name: ParseForMe
provenance_date: '2026-11-10'
provider_name: ParseForMe
provider_slug: parseforme
slug: parseforme-eligibility
source_date: '2026-11-10'
source_filename: parseforme-eligibility.yml
source_heading: Eligibility
source_page: https://parseforme.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ParseForMe\naid: parseforme\nurl: https://parseforme.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\nrestricted_uses:\n- summary: Unlawful content\n  text: You must not upload unlawful content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/parseforme/eligibility/parseforme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ParseForMe's own page on 2026-11-10.
synthetic: false
tags:
- Document Parsing
- OCR
- Data Extraction
- Document AI
- Intelligent Document Processing
- Invoices
- Bank Statements
- Receipts
- Resume
- PDF
- Webhook
- REST
---
