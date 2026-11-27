---
api_specs:
- filename: yardi-billing-and-payments-api-openapi.yml
  format: yaml
  label: Yardi Billing and Payments Interface
  slug: yardi-billing-and-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-billing-and-payments-api-openapi.yml
- filename: yardi-common-data-api-openapi.yml
  format: yaml
  label: Yardi Common Data Interface
  slug: yardi-common-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-common-data-api-openapi.yml
- filename: yardi-job-cost-api-openapi.yml
  format: yaml
  label: Yardi Job Cost Interface
  slug: yardi-job-cost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-job-cost-api-openapi.yml
- filename: yardi-service-requests-api-openapi.yml
  format: yaml
  label: Yardi Service Requests Interface
  slug: yardi-service-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-service-requests-api-openapi.yml
- filename: yardi-vendor-invoicing-api-openapi.yml
  format: yaml
  label: Yardi Vendor Invoicing Interface
  slug: yardi-vendor-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-vendor-invoicing-api-openapi.yml
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
  - summary: Common Clients only
    text: Company shall not use the Data Exchange Program to provide programming services or any other services for non-Common Clients.
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
name: Yardi
provenance_date: '2026-11-10'
provider_name: Yardi
provider_slug: yardi
slug: yardi-eligibility
source_date: '2026-11-10'
source_filename: yardi-eligibility.yml
source_heading: Eligibility
source_page: https://resources.yardi.com/legal/rc-api-tou/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yardi\naid: yardi\nurl: https://resources.yardi.com/legal/rc-api-tou/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Common Clients only\n  text: Company shall not use the Data Exchange Program to provide programming services or any other services for\n    non-Common Clients.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yardi/eligibility/yardi-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Yardi's own page on 2026-11-10.
synthetic: false
tags:
- Accounting
- Commercial Real Estate
- Co-Working
- Investment Management
- MCP
- Multifamily
- Property Management
- PropTech
- Real Estate
- Residential
- Self Storage
- Senior Living
---
