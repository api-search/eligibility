---
api_specs:
- filename: dext-clients-api-openapi.yml
  format: yaml
  label: Dext Clients API
  slug: dext-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dext/openapi/dext-clients-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You understand that the Dext Products are provided for business use only.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Business use only
    text: You understand that the Dext Products are provided for business use only.
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
name: Dext
provenance_date: '2026-11-09'
provider_name: Dext
provider_slug: dext
slug: dext-eligibility
source_date: '2026-11-09'
source_filename: dext-eligibility.yml
source_heading: Eligibility
source_page: https://dext.com/us/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dext\naid: dext\nurl: https://dext.com/us/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You understand that the Dext Products are provided for business use only.\nrestricted_uses:\n- summary: Business use only\n  text: You understand that the Dext Products are provided for business use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dext/eligibility/dext-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dext's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Bookkeeping
- Receipts
- Expense Management
- Financial Automation
- Data Health
- OCR
---
