---
api_specs:
- filename: scanner-ad-hoc-queries-api-openapi.yml
  format: yaml
  label: Scanner Ad Hoc Queries API
  slug: scanner-ad-hoc-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-ad-hoc-queries-api-openapi.yml
- filename: scanner-detection-rules-api-openapi.yml
  format: yaml
  label: Scanner Detection Rules API
  slug: scanner-detection-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-detection-rules-api-openapi.yml
- filename: scanner-event-sinks-api-openapi.yml
  format: yaml
  label: Scanner Event Sinks API
  slug: scanner-event-sinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-event-sinks-api-openapi.yml
- filename: scanner-indexes-api-openapi.yml
  format: yaml
  label: Scanner Indexes API
  slug: scanner-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-indexes-api-openapi.yml
- filename: scanner-info-api-openapi.yml
  format: yaml
  label: Scanner Info API
  slug: scanner-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-info-api-openapi.yml
- filename: scanner-lookup-tables-api-openapi.yml
  format: yaml
  label: Scanner Lookup Tables API
  slug: scanner-lookup-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-lookup-tables-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services are not directed to, and we do not knowingly collect personal information from, anyone under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Unlawful use
    text: use, or facilitate use of, the Site or Services in a manner, which violates any applicable law or regulation.
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
name: Scanner
provenance_date: '2026-11-10'
provider_name: Scanner
provider_slug: scanner
slug: scanner-eligibility
source_date: '2026-11-10'
source_filename: scanner-eligibility.yml
source_heading: Eligibility
source_page: https://scanner.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scanner\naid: scanner\nurl: https://scanner.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: use, or facilitate use of, the Site or Services in a manner, which violates any applicable law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are not directed to, and we do not knowingly collect personal information from, anyone under\n    the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/scanner/eligibility/scanner-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Scanner's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- SIEM
- Log Analytics
- Threat Detection
- Security Operations
- Observability
- MCP
---
