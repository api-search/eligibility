---
api_specs:
- filename: xero-accounting-api-openapi.yml
  format: yaml
  label: Xero Accounting API
  slug: xero-accounting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-accounting-api-openapi.yml
- filename: xero-asset-api-openapi.yml
  format: yaml
  label: Xero Asset API
  slug: xero-asset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-asset-api-openapi.yml
- filename: xero-files-api-openapi.yml
  format: yaml
  label: Xero Files API
  slug: xero-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-files-api-openapi.yml
- filename: xero-finance-api-openapi.yml
  format: yaml
  label: Xero Finance API
  slug: xero-finance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-finance-api-openapi.yml
- filename: xero-identity-api-openapi.yml
  format: yaml
  label: Xero Identity API
  slug: xero-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-identity-api-openapi.yml
- filename: xero-payrollau-api-openapi.yml
  format: yaml
  label: Xero PayrollAu API
  slug: xero-payrollau-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-payrollau-api-openapi.yml
- filename: xero-payrollnz-api-openapi.yml
  format: yaml
  label: Xero PayrollNz API
  slug: xero-payrollnz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-payrollnz-api-openapi.yml
- filename: xero-payrolluk-api-openapi.yml
  format: yaml
  label: Xero PayrollUk API
  slug: xero-payrolluk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-payrolluk-api-openapi.yml
- filename: xero-project-api-openapi.yml
  format: yaml
  label: Xero Project API
  slug: xero-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-project-api-openapi.yml
- filename: xero-accountdata-api-openapi.yml
  format: yaml
  label: Xero Account Data API
  slug: xero-accountdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-accountdata-api-openapi.yml
- filename: xero-feedconnections-api-openapi.yml
  format: yaml
  label: Xero Feed Connections API
  slug: xero-feedconnections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-feedconnections-api-openapi.yml
- filename: xero-app-store-api-openapi.yml
  format: yaml
  label: Xero App Store API
  slug: xero-app-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-app-store-api-openapi.yml
- filename: xero-bank-feeds-api-openapi.yml
  format: yaml
  label: Xero Bank Feeds API
  slug: xero-bank-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xero/openapi/xero-bank-feeds-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You promise that you’re not located in a sanctioned country and are not on a sanctioned persons list.
  entity_types:
  - text: if you’re agreeing to these terms on behalf of any entity, that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Financial services need approval
    text: Access or use the developer platform to provide financial services without our approval.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: You are responsible for making sure your app’s use cases have been approved by us
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Xero
provenance_date: '2026-11-10'
provider_name: Xero
provider_slug: xero
slug: xero-eligibility
source_date: '2026-11-10'
source_filename: xero-eligibility.yml
source_heading: Eligibility
source_page: https://developer.xero.com/xero-developer-platform-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xero\naid: xero\nurl: https://developer.xero.com/xero-developer-platform-terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You promise that you’re not located in a sanctioned country and are not on a sanctioned persons list.\nentity_types:\n- type: business\n  text: if you’re agreeing to these terms on behalf of any entity, that entity\nrestricted_uses:\n- summary: Financial services need approval\n  text: Access or use the developer platform to provide financial services without our approval.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text:\
  \ You are responsible for making sure your app’s use cases have been approved by us\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xero/eligibility/xero-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Xero's own page on 2026-11-10.
synthetic: false
tags:
- Accounting
- Bank Feeds
- Finance
- Financial Services
- Invoicing
- Payroll
- Small Business
---
