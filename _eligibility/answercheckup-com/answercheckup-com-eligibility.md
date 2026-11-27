---
api_specs:
- filename: answercheckup-com-pricing-api-openapi.yml
  format: yaml
  label: Answer Checkup Pricing API
  slug: answercheckup-com-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-pricing-api-openapi.yml
- filename: answercheckup-com-report-api-openapi.yml
  format: yaml
  label: Answer Checkup Report API
  slug: answercheckup-com-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-report-api-openapi.yml
- filename: answercheckup-com-reports-api-openapi.yml
  format: yaml
  label: Answer Checkup Reports API
  slug: answercheckup-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-reports-api-openapi.yml
- filename: answercheckup-com-scan-api-openapi.yml
  format: yaml
  label: Answer Checkup Scan API
  slug: answercheckup-com-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-scan-api-openapi.yml
- filename: answercheckup-com-scan-details-api-openapi.yml
  format: yaml
  label: Answer Checkup Scan Details API
  slug: answercheckup-com-scan-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-scan-details-api-openapi.yml
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
  - summary: Only own or permitted sites
    text: Only scan or report on websites you own or are allowed to check.
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
name: Answer Checkup
provenance_date: '2026-11-09'
provider_name: Answer Checkup
provider_slug: answercheckup-com
slug: answercheckup-com-eligibility
source_date: '2026-11-09'
source_filename: answercheckup-com-eligibility.yml
source_heading: Eligibility
source_page: https://answercheckup.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Answer Checkup\naid: answercheckup-com\nurl: https://answercheckup.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Only own or permitted sites\n  text: Only scan or report on websites you own or are allowed to check.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/answercheckup-com/eligibility/answercheckup-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Answer Checkup's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- SEO
- Marketing
- Analytics
- Business
---
