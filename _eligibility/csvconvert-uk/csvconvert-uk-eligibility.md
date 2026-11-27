---
api_specs:
- filename: csvconvert-uk-enquiry-api-openapi.yml
  format: yaml
  label: CSV Convert Enquiry API
  slug: csvconvert-uk-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/csvconvert-uk/openapi/csvconvert-uk-enquiry-api-openapi.yml
- filename: csvconvert-uk-guide-api-openapi.yml
  format: yaml
  label: CSV Convert Guide API
  slug: csvconvert-uk-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/csvconvert-uk/openapi/csvconvert-uk-guide-api-openapi.yml
- filename: csvconvert-uk-mcp-api-openapi.yml
  format: yaml
  label: CSV Convert MCP API
  slug: csvconvert-uk-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/csvconvert-uk/openapi/csvconvert-uk-mcp-api-openapi.yml
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
  - summary: No regulated advice
    text: Nothing here is financial, legal, tax, medical or other regulated advice
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
name: CSV Convert
provenance_date: '2026-11-09'
provider_name: CSV Convert
provider_slug: csvconvert-uk
slug: csvconvert-uk-eligibility
source_date: '2026-11-09'
source_filename: csvconvert-uk-eligibility.yml
source_heading: Eligibility
source_page: https://csvconvert.uk/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CSV Convert\naid: csvconvert-uk\nurl: https://csvconvert.uk/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No regulated advice\n  text: Nothing here is financial, legal, tax, medical or other regulated advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/csvconvert-uk/eligibility/csvconvert-uk-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CSV Convert's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CSV
- PDF
- Data Conversion
- Data Extraction
- OCR
- United Kingdom
- Data Protection
---
