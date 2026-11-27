---
api_specs:
- filename: funding-circle-decisions-api-openapi.yml
  format: yaml
  label: Funding Circle Decisions API
  slug: funding-circle-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/funding-circle/openapi/funding-circle-decisions-api-openapi.yml
- filename: funding-circle-documents-api-openapi.yml
  format: yaml
  label: Funding Circle Documents API
  slug: funding-circle-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/funding-circle/openapi/funding-circle-documents-api-openapi.yml
- filename: funding-circle-loan-applications-api-openapi.yml
  format: yaml
  label: Funding Circle Loan Applications API
  slug: funding-circle-loan-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/funding-circle/openapi/funding-circle-loan-applications-api-openapi.yml
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
  - summary: Unlawful or fraudulent use
    text: use the Website and/or Funding Circle Platform for any purpose that is unlawful, including any fraudulent use
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
name: Funding Circle
provenance_date: '2026-11-09'
provider_name: Funding Circle
provider_slug: funding-circle
slug: funding-circle-eligibility
source_date: '2026-11-09'
source_filename: funding-circle-eligibility.yml
source_heading: Eligibility
source_page: https://www.fundingcircle.com/uk/legal/platform-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Funding Circle\naid: funding-circle\nurl: https://www.fundingcircle.com/uk/legal/platform-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: use the Website and/or Funding Circle Platform for any purpose that is unlawful, including any fraudulent\n    use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/funding-circle/eligibility/funding-circle-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Funding Circle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Lending
- Small Business
- Fintech
- Loans
- Financial Services
- Payments
---
