---
api_specs:
- filename: lastdatabase-leads-api-openapi.yml
  format: yaml
  label: LastDatabase Leads API
  slug: lastdatabase-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastdatabase/openapi/lastdatabase-leads-api-openapi.yml
claim_count: 2
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
  - summary: Violation of privacy or marketing laws
    text: Violation of applicable privacy or marketing laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require email verification or other reasonable account verification before certain features become available.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LastDatabase
provenance_date: '2026-11-09'
provider_name: LastDatabase
provider_slug: lastdatabase
slug: lastdatabase-eligibility
source_date: '2026-11-09'
source_filename: lastdatabase-eligibility.yml
source_heading: Eligibility
source_page: https://lastdatabase.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LastDatabase\naid: lastdatabase\nurl: https://lastdatabase.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Violation of privacy or marketing laws\n  text: Violation of applicable privacy or marketing laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require email verification or other reasonable account verification before certain features become\n    available.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lastdatabase/eligibility/lastdatabase-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from LastDatabase's own page on 2026-11-09.
synthetic: false
tags:
- Contact Data
- Lead Generation
- B2B Data
- Email Verification
- Data Enrichment
- Sales Prospecting
- MCP
---
