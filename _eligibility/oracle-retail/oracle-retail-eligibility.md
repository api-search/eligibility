---
api_specs:
- filename: oracle-retail-fulfillment-api-openapi.yml
  format: yaml
  label: Oracle Retail Fulfillment API
  slug: oracle-retail-fulfillment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oracle-retail/openapi/oracle-retail-fulfillment-api-openapi.yml
- filename: oracle-retail-inventory-api-openapi.yml
  format: yaml
  label: Oracle Retail Inventory API
  slug: oracle-retail-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oracle-retail/openapi/oracle-retail-inventory-api-openapi.yml
- filename: oracle-retail-items-api-openapi.yml
  format: yaml
  label: Oracle Retail Items API
  slug: oracle-retail-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oracle-retail/openapi/oracle-retail-items-api-openapi.yml
- filename: oracle-retail-orders-api-openapi.yml
  format: yaml
  label: Oracle Retail Orders API
  slug: oracle-retail-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oracle-retail/openapi/oracle-retail-orders-api-openapi.yml
- filename: oracle-retail-returns-api-openapi.yml
  format: yaml
  label: Oracle Retail Returns API
  slug: oracle-retail-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oracle-retail/openapi/oracle-retail-returns-api-openapi.yml
- filename: oracle-retail-suppliers-api-openapi.yml
  format: yaml
  label: Oracle Retail Suppliers API
  slug: oracle-retail-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oracle-retail/openapi/oracle-retail-suppliers-api-openapi.yml
- filename: oracle-retail-purchase-orders-api-openapi.yml
  format: yaml
  label: Oracle Retail Purchase Orders API
  slug: oracle-retail-purchase-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oracle-retail/openapi/oracle-retail-purchase-orders-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Neither the services or products of Oracle nor the underlying information or technology may be downloaded or otherwise provided or made available, either directly or indirectly, into any country subject to U.S. trade sanctions
  minimum_age:
    text: Persons who are not of the age of majority are not eligible to use the Site
    value: age of majority
  restricted_uses:
  - summary: Export law compliance
    text: You may not access, download, use or export the Site, or the Content provided on or through the Site, in violation of U.S. export laws or regulations
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
name: Oracle Retail
provenance_date: '2026-11-10'
provider_name: Oracle Retail
provider_slug: oracle-retail
slug: oracle-retail-eligibility
source_date: '2026-11-10'
source_filename: oracle-retail-eligibility.yml
source_heading: Eligibility
source_page: https://www.oracle.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oracle Retail\naid: oracle-retail\nurl: https://www.oracle.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Neither the services or products of Oracle nor the underlying information or technology may be downloaded\n    or otherwise provided or made available, either directly or indirectly, into any country subject to U.S. trade\n    sanctions\nentity_types: []\nrestricted_uses:\n- summary: Export law compliance\n  text: You may not access, download, use or export the Site, or the Content provided on or through the Site, in\n    violation of U.S. export laws or regulations\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: Persons who are not of the age of majority are not eligible to use the Site\n"
source_yaml_url: https://artifacts.apis.io/oracle-retail/eligibility/oracle-retail-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Oracle Retail's own page on 2026-11-10.
synthetic: false
tags:
- Retail
- Merchandising
- Order Management
- Pricing
- Inventory
- Point-of-Sale
- Omnichannel
- Oracle
---
