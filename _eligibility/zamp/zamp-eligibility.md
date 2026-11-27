---
api_specs:
- filename: zamp-openapi-generated.yml
  format: yaml
  label: Zamp API
  slug: zamp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zamp/openapi/_ae-authored/zamp-openapi-generated.yml
- filename: zamp-addresses-api-openapi.yml
  format: yaml
  label: Zamp Addresses API
  slug: zamp-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zamp/openapi/zamp-addresses-api-openapi.yml
- filename: zamp-calculations-api-openapi.yml
  format: yaml
  label: Zamp Calculations API
  slug: zamp-calculations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zamp/openapi/zamp-calculations-api-openapi.yml
- filename: zamp-companies-api-openapi.yml
  format: yaml
  label: Zamp Companies API
  slug: zamp-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zamp/openapi/zamp-companies-api-openapi.yml
- filename: zamp-filings-api-openapi.yml
  format: yaml
  label: Zamp Filings API
  slug: zamp-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zamp/openapi/zamp-filings-api-openapi.yml
- filename: zamp-registrations-api-openapi.yml
  format: yaml
  label: Zamp Registrations API
  slug: zamp-registrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zamp/openapi/zamp-registrations-api-openapi.yml
- filename: zamp-tax-codes-api-openapi.yml
  format: yaml
  label: Zamp Tax Codes API
  slug: zamp-tax-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zamp/openapi/zamp-tax-codes-api-openapi.yml
- filename: zamp-transactions-api-openapi.yml
  format: yaml
  label: Zamp Transactions API
  slug: zamp-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zamp/openapi/zamp-transactions-api-openapi.yml
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
  - summary: Fraudulent API requests
    text: use the API to send fraudulent requests
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
name: Zamp
provenance_date: '2026-11-10'
provider_name: Zamp
provider_slug: zamp
slug: zamp-eligibility
source_date: '2026-11-10'
source_filename: zamp-eligibility.yml
source_heading: Eligibility
source_page: https://zamp.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zamp\naid: zamp\nurl: https://zamp.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent API requests\n  text: use the API to send fraudulent requests\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zamp/eligibility/zamp-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Zamp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales Tax
- Automation
- Compliance
---
