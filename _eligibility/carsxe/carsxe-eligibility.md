---
api_specs:
- filename: carsxe-specifications-api-openapi.yml
  format: yaml
  label: CarsXE Specifications API
  slug: carsxe-specifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-specifications-api-openapi.yml
- filename: carsxe-market-value-api-openapi.yml
  format: yaml
  label: CarsXE Market Value API
  slug: carsxe-market-value-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-market-value-api-openapi.yml
- filename: carsxe-recalls-api-openapi.yml
  format: yaml
  label: CarsXE Recalls API
  slug: carsxe-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-recalls-api-openapi.yml
- filename: carsxe-history-api-openapi.yml
  format: yaml
  label: CarsXE History API
  slug: carsxe-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-history-api-openapi.yml
- filename: carsxe-images-api-openapi.yml
  format: yaml
  label: CarsXE Images API
  slug: carsxe-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-images-api-openapi.yml
- filename: carsxe-recognition-api-openapi.yml
  format: yaml
  label: CarsXE Recognition API
  slug: carsxe-recognition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-recognition-api-openapi.yml
- filename: carsxe-year-make-model-api-openapi.yml
  format: yaml
  label: CarsXE Year Make Model API
  slug: carsxe-year-make-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-year-make-model-api-openapi.yml
- filename: carsxe-lien-theft-api-openapi.yml
  format: yaml
  label: CarsXE Lien & Theft API
  slug: carsxe-lien-theft-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-lien-theft-api-openapi.yml
- filename: carsxe-auth-api-openapi.yml
  format: yaml
  label: CarsXE Auth API
  slug: carsxe-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-auth-api-openapi.yml
- filename: carsxe-plate-decoder-api-openapi.yml
  format: yaml
  label: CarsXE Plate Decoder API
  slug: carsxe-plate-decoder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-plate-decoder-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We offer you access to the CarsXE website solely for your own personal and non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only
    text: You may not resell or make any commercial use of this website and its content.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access the services on this site, you will be required to use an account and password that can be obtained by completing our online registration form
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CarsXE
provenance_date: '2026-11-09'
provider_name: CarsXE
provider_slug: carsxe
slug: carsxe-eligibility
source_date: '2026-11-09'
source_filename: carsxe-eligibility.yml
source_heading: Eligibility
source_page: https://carsxe.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CarsXE\naid: carsxe\nurl: https://carsxe.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We offer you access to the CarsXE website solely for your own personal and non-commercial use.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You may not resell or make any commercial use of this website and its content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access the services on this site, you will be required to use an account and password that can\n\
  \    be obtained by completing our online registration form\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carsxe/eligibility/carsxe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from CarsXE's own page on 2026-11-09.
synthetic: false
tags:
- Automotive
- Vehicles
- VIN
- Vehicle Data
- License Plate
- OCR
- Automobiles
- Recalls
- Market Value
- Vehicle History
- MCP
- Agents
---
