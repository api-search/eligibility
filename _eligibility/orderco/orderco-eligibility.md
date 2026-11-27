---
api_specs:
- filename: orderco-components-api-openapi.yml
  format: yaml
  label: Order.co Components API
  slug: orderco-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderco/openapi/orderco-components-api-openapi.yml
- filename: orderco-incidents-api-openapi.yml
  format: yaml
  label: Order.co Incidents API
  slug: orderco-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderco/openapi/orderco-incidents-api-openapi.yml
- filename: orderco-maintenance-api-openapi.yml
  format: yaml
  label: Order.co Maintenance API
  slug: orderco-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderco/openapi/orderco-maintenance-api-openapi.yml
- filename: orderco-status-api-openapi.yml
  format: yaml
  label: Order.co Status API
  slug: orderco-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderco/openapi/orderco-status-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the business or legal entity that is applying for or has opened an Order Profile to use the Services.
    type: business
  minimum_age:
    text: (i) is at least 18 years of age
    value: '18'
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
name: Order.co
provenance_date: '2026-11-10'
provider_name: Order.co
provider_slug: orderco
slug: orderco-eligibility
source_date: '2026-11-10'
source_filename: orderco-eligibility.yml
source_heading: Eligibility
source_page: https://www.order.co/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Order.co\naid: orderco\nurl: https://www.order.co/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the business or legal entity that is applying for or has opened an Order Profile to use the Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (i) is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/orderco/eligibility/orderco-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Order.co's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Procurement
- Spend Management
- Accounts Payable
- Purchasing
- Vendor Management
- Payments
- Virtual Cards
- Finance Automation
- United States
---
