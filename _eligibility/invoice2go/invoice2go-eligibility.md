---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Invoice2go makes no representations that the Product is appropriate or available for use outside the United States.
  entity_types:
  - text: You must be at least 18 years of age to use the Product.
    type: individual
  - text: The Product is designed to be used for business purposes. You represent and warrant that you are using the product for business purposes
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Product.
    value: '18'
  restricted_uses:
  - summary: No high-risk activities
    text: Customer further agrees not to use the Product for activities where use or failure of the Product could lead to death, personal injury or environmental damage, including life support systems, emergency services, nuclear facilities, autonomous vehicles or air traffic control
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
name: Invoice2go
provenance_date: '2026-11-09'
provider_name: Invoice2go
provider_slug: invoice2go
slug: invoice2go-eligibility
source_date: '2026-11-09'
source_filename: invoice2go-eligibility.yml
source_heading: Eligibility
source_page: https://invoice.2go.com:443/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Invoice2go\naid: invoice2go\nurl: https://invoice.2go.com:443/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Invoice2go makes no representations that the Product is appropriate or available for use outside the United\n    States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Product.\n- type: business\n  text: The Product is designed to be used for business purposes. You represent and warrant that you are using the\n    product for business purposes\nrestricted_uses:\n- summary: No high-risk activities\n\
  \  text: Customer further agrees not to use the Product for activities where use or failure of the Product could\n    lead to death, personal injury or environmental damage, including life support systems, emergency services,\n    nuclear facilities, autonomous vehicles or air traffic control\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Product.\n"
source_yaml_url: https://artifacts.apis.io/invoice2go/eligibility/invoice2go-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Invoice2go's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Invoicing
- Payments
- Small Business
- Accounting
- Estimates
- Expense Management
---
