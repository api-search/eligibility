---
api_specs:
- filename: shippit-book-api-openapi.yml
  format: yaml
  label: Shippit Book API
  slug: shippit-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-book-api-openapi.yml
- filename: shippit-label-api-openapi.yml
  format: yaml
  label: Shippit Label API
  slug: shippit-label-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-label-api-openapi.yml
- filename: shippit-merchant-api-openapi.yml
  format: yaml
  label: Shippit Merchant API
  slug: shippit-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-merchant-api-openapi.yml
- filename: shippit-orders-api-openapi.yml
  format: yaml
  label: Shippit Orders API
  slug: shippit-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-orders-api-openapi.yml
- filename: shippit-quote-api-openapi.yml
  format: yaml
  label: Shippit Quote API
  slug: shippit-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-quote-api-openapi.yml
- filename: shippit-tracking-api-openapi.yml
  format: yaml
  label: Shippit Tracking API
  slug: shippit-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-tracking-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    - NZ
    text: 'Shippit means Shippit Pty Ltd ACN 169 407 747 in reference to a Customer domiciled in Australia or New Zealand and Shippit Pte Ltd (UEN: 201806240K) in reference to a Customer domiciled in any other country in the APAC region (including without limitation Singapore, Malaysia, Indonesia, the Philippines and China).'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited Items shipments
    text: The Customer cannot use the Services in order to send Prohibited Items.
  - summary: Fraudulent, illegal or unauthorised use
    text: Customer engages in fraudulent, illegal or unauthorised use of the Services
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
name: Shippit
provenance_date: '2026-11-10'
provider_name: Shippit
provider_slug: shippit
slug: shippit-eligibility
source_date: '2026-11-10'
source_filename: shippit-eligibility.yml
source_heading: Eligibility
source_page: https://www.shippit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shippit\naid: shippit\nurl: https://www.shippit.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  - NZ\n  excluded: []\n  text: 'Shippit means Shippit Pty Ltd ACN 169 407 747 in reference to a Customer domiciled in Australia or New\n    Zealand and Shippit Pte Ltd (UEN: 201806240K) in reference to a Customer domiciled in any other country in the\n    APAC region (including without limitation Singapore, Malaysia, Indonesia, the Philippines and China).'\nentity_types: []\nrestricted_uses:\n- summary: Prohibited Items shipments\n  text: The Customer cannot use the Services in order to send Prohibited\
  \ Items.\n- summary: Fraudulent, illegal or unauthorised use\n  text: Customer engages in fraudulent, illegal or unauthorised use of the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shippit/eligibility/shippit-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Shippit's own page on 2026-11-10.
synthetic: false
tags:
- Shipping
- Logistics
- Fulfillment
- Australia
- Asia Pacific
- Multi-Carrier
- Labels
- Tracking
- Parcel
- E-commerce Logistics
- Software-as-a-Service
---
