---
api_specs:
- filename: runbuggy-companies-api-openapi.yml
  format: yaml
  label: RunBuggy Companies API
  slug: runbuggy-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runbuggy/openapi/runbuggy-companies-api-openapi.yml
- filename: runbuggy-orders-api-openapi.yml
  format: yaml
  label: RunBuggy Orders API
  slug: runbuggy-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runbuggy/openapi/runbuggy-orders-api-openapi.yml
- filename: runbuggy-token-api-openapi.yml
  format: yaml
  label: RunBuggy Token API
  slug: runbuggy-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runbuggy/openapi/runbuggy-token-api-openapi.yml
- filename: runbuggy-vehicle-transfer-orders-api-openapi.yml
  format: yaml
  label: RunBuggy Vehicle Transfer Orders API
  slug: runbuggy-vehicle-transfer-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runbuggy/openapi/runbuggy-vehicle-transfer-orders-api-openapi.yml
- filename: runbuggy-webhooks-api-openapi.yml
  format: yaml
  label: RunBuggy Webhooks API
  slug: runbuggy-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runbuggy/openapi/runbuggy-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Shipping services described as provided in the United States and Canada (state, provincial and federal regulations referenced).
  minimum_age:
    text: The RunBuggy Service is available only to Users who have reached the applicable age of majority in the province or state in which such User resides
    value: age of majority
  restricted_uses:
  - summary: Illegal or unsafe use
    text: not use the RunBuggy Service for any illegal, unauthorized, unintended, unsafe, hazardous, or unlawful purposes.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: RunBuggy reserves the right to designate a third-party service provider to independently verify the documentation, insurance, and background checks required by this section.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RunBuggy
provenance_date: '2026-11-10'
provider_name: RunBuggy
provider_slug: runbuggy
slug: runbuggy-eligibility
source_date: '2026-11-10'
source_filename: runbuggy-eligibility.yml
source_heading: Eligibility
source_page: https://runbuggy.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RunBuggy\naid: runbuggy\nurl: https://runbuggy.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Shipping services described as provided in the United States and Canada (state, provincial and federal regulations\n    referenced).\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unsafe use\n  text: not use the RunBuggy Service for any illegal, unauthorized, unintended, unsafe, hazardous, or unlawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: RunBuggy reserves the right to designate a third-party\
  \ service provider to independently verify the documentation,\n    insurance, and background checks required by this section.\nminimum_age:\n  value: age of majority\n  text: The RunBuggy Service is available only to Users who have reached the applicable age of majority in the province\n    or state in which such User resides\n"
source_yaml_url: https://artifacts.apis.io/runbuggy/eligibility/runbuggy-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from RunBuggy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automotive
- Logistics
- Transportation
- Vehicle Shipping
- Marketplace
- Supply Chain
- Fleet Management
- TMS
- Freight
---
