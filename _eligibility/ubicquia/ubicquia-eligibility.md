---
api_specs:
- filename: ubicquia-authcheck-api-openapi.yml
  format: yaml
  label: Ubicquia Auth Check API
  slug: ubicquia-authcheck-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-authcheck-api-openapi.yml
- filename: ubicquia-customer-detail-api-openapi.yml
  format: yaml
  label: Ubicquia Customer Detail API
  slug: ubicquia-customer-detail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-customer-detail-api-openapi.yml
- filename: ubicquia-fulfillment-details-api-openapi.yml
  format: yaml
  label: Ubicquia Fulfillment Details API
  slug: ubicquia-fulfillment-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-fulfillment-details-api-openapi.yml
- filename: ubicquia-iccid-master-api-openapi.yml
  format: yaml
  label: Ubicquia ICCID Master API
  slug: ubicquia-iccid-master-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-iccid-master-api-openapi.yml
- filename: ubicquia-sales-order-api-openapi.yml
  format: yaml
  label: Ubicquia Sales Order API
  slug: ubicquia-sales-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-sales-order-api-openapi.yml
- filename: ubicquia-serial-number-api-openapi.yml
  format: yaml
  label: Ubicquia Serial Number API
  slug: ubicquia-serial-number-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-serial-number-api-openapi.yml
- filename: ubicquia-transformer-details-api-openapi.yml
  format: yaml
  label: Ubicquia Transformer Details API
  slug: ubicquia-transformer-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-transformer-details-api-openapi.yml
- filename: ubicquia-user-api-openapi.yml
  format: yaml
  label: Ubicquia User API
  slug: ubicquia-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-user-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is a business-focused, non-consumer oriented Internet-accessible website that performs or provides one or more web-based Services to Users other than consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Military, nuclear, missile, chemical or biological end uses
    text: agree not to use UBICQUIA’S Website and/or Services for any military, nuclear, missile, chemical, or biological weaponry end uses that would be a violation of the U.S. export laws
  - summary: Export-prohibited parties and countries
    text: agree not to transfer any software, technology, technical information, multimedia, and the like through the use of UBICQUIA’S Website and/or Services to any export-prohibited country
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
name: Ubicquia
provenance_date: '2026-11-10'
provider_name: Ubicquia
provider_slug: ubicquia
slug: ubicquia-eligibility
source_date: '2026-11-10'
source_filename: ubicquia-eligibility.yml
source_heading: Eligibility
source_page: https://www.ubicquia.com/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ubicquia\naid: ubicquia\nurl: https://www.ubicquia.com/terms-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Website is a business-focused, non-consumer oriented Internet-accessible website that performs or provides\n    one or more web-based Services to Users other than consumers.\nrestricted_uses:\n- summary: Military, nuclear, missile, chemical or biological end uses\n  text: agree not to use UBICQUIA’S Website and/or Services for any military, nuclear, missile, chemical, or biological\n    weaponry end uses that would be\
  \ a violation of the U.S. export laws\n- summary: Export-prohibited parties and countries\n  text: agree not to transfer any software, technology, technical information, multimedia, and the like through\n    the use of UBICQUIA’S Website and/or Services to any export-prohibited country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ubicquia/eligibility/ubicquia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Ubicquia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Smart Cities
- IoT
- Energy
- Utilities
- Electric Grid
- Streetlights
- Public Safety
- Infrastructure
- Sensors
- Edge AI
- Transformer Monitoring
---
