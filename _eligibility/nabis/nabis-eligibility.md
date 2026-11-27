---
api_specs:
- filename: nabis-collection-api-openapi.yml
  format: yaml
  label: Nabis Collection API
  slug: nabis-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-collection-api-openapi.yml
- filename: nabis-inventory-api-openapi.yml
  format: yaml
  label: Nabis Inventory API
  slug: nabis-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-inventory-api-openapi.yml
- filename: nabis-inventory-history-api-openapi.yml
  format: yaml
  label: Nabis Inventory History API
  slug: nabis-inventory-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-inventory-history-api-openapi.yml
- filename: nabis-invoice-api-openapi.yml
  format: yaml
  label: Nabis Invoice API
  slug: nabis-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-invoice-api-openapi.yml
- filename: nabis-invoices-api-openapi.yml
  format: yaml
  label: Nabis Invoices API
  slug: nabis-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-invoices-api-openapi.yml
- filename: nabis-nabisdaysoff-api-openapi.yml
  format: yaml
  label: Nabis Days Off API
  slug: nabis-nabisdaysoff-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-nabisdaysoff-api-openapi.yml
- filename: nabis-ny-inventory-api-openapi.yml
  format: yaml
  label: Nabis NY Inventory API
  slug: nabis-ny-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-ny-inventory-api-openapi.yml
- filename: nabis-ny-invoice-api-openapi.yml
  format: yaml
  label: Nabis NY Invoice API
  slug: nabis-ny-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-ny-invoice-api-openapi.yml
- filename: nabis-ny-order-api-openapi.yml
  format: yaml
  label: Nabis NY Order API
  slug: nabis-ny-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-ny-order-api-openapi.yml
- filename: nabis-ny-retailer-api-openapi.yml
  format: yaml
  label: Nabis NY Retailer API
  slug: nabis-ny-retailer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-ny-retailer-api-openapi.yml
- filename: nabis-nywarehouse-api-openapi.yml
  format: yaml
  label: Nabis NY Warehouse API
  slug: nabis-nywarehouse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-nywarehouse-api-openapi.yml
- filename: nabis-order-api-openapi.yml
  format: yaml
  label: Nabis Order API
  slug: nabis-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-order-api-openapi.yml
- filename: nabis-orders-api-openapi.yml
  format: yaml
  label: Nabis Orders API
  slug: nabis-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-orders-api-openapi.yml
- filename: nabis-retailer-api-openapi.yml
  format: yaml
  label: Nabis Retailer API
  slug: nabis-retailer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-retailer-api-openapi.yml
- filename: nabis-sku-api-openapi.yml
  format: yaml
  label: Nabis Sku API
  slug: nabis-sku-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-sku-api-openapi.yml
- filename: nabis-skubatch-api-openapi.yml
  format: yaml
  label: Nabis Skubatch API
  slug: nabis-skubatch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-skubatch-api-openapi.yml
- filename: nabis-universal-cannabis-labeling-api-openapi.yml
  format: yaml
  label: Nabis Universal Cannabis Labeling API
  slug: nabis-universal-cannabis-labeling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-universal-cannabis-labeling-api-openapi.yml
- filename: nabis-warehouses-api-openapi.yml
  format: yaml
  label: Nabis Warehouses API
  slug: nabis-warehouses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabis/openapi/nabis-warehouses-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'Country refers to: California, United States'
  entity_types:
  - text: You means the individual accessing or using the Application or the company, or other legal entity on behalf of which such individual is accessing or using the Application, as applicable.
    type: individual
  - text: You means the individual accessing or using the Application or the company, or other legal entity on behalf of which such individual is accessing or using the Application, as applicable.
    type: business
  minimum_age:
    text: You represent that you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: The license that is granted to You by the Company is solely for your personal, non-commercial purposes strictly in accordance with the terms of this Agreement.
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
name: Nabis
provenance_date: '2026-11-10'
provider_name: Nabis
provider_slug: nabis
slug: nabis-eligibility
source_date: '2026-11-10'
source_filename: nabis-eligibility.yml
source_heading: Eligibility
source_page: https://www.nabis.com/legal/license-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nabis\naid: nabis\nurl: https://www.nabis.com/legal/license-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'Country refers to: California, United States'\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Application or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Application, as applicable.\n- type: business\n  text: You means the individual accessing or using the Application or the company, or other legal entity on behalf\n    of which such individual is accessing or\
  \ using the Application, as applicable.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: The license that is granted to You by the Company is solely for your personal, non-commercial purposes strictly\n    in accordance with the terms of this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/nabis/eligibility/nabis-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nabis's own page on 2026-11-10.
synthetic: false
tags:
- Cannabis
- Distribution
- Wholesale
- Marketplace
- Logistics
- Supply Chain
- Inventory
- Order
- Invoicing
- Retail
- Compliance
- Track and Trace
- California
- New York
---
