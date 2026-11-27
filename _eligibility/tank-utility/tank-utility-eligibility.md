---
api_specs:
- filename: tank-utility-authentication-api-openapi.yml
  format: yaml
  label: Tank Utility Authentication API
  slug: tank-utility-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tank-utility/openapi/tank-utility-authentication-api-openapi.yml
- filename: tank-utility-devices-api-openapi.yml
  format: yaml
  label: Tank Utility Devices API
  slug: tank-utility-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tank-utility/openapi/tank-utility-devices-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Products and Services are not available to all persons or in all countries; Sites are designed for Target Countries where Tank Utility supports the Product.
  entity_types:
  - text: You may use the Services only if you can form a binding contract with Tank Utility
    type: individual
  minimum_age:
    text: Any use or access to the Services by anyone under the age of 18 is strictly prohibited and is a violation of these Terms.
    value: '18'
  restricted_uses:
  - summary: No life safety or critical uses
    text: YOU AGREE THAT YOU WILL NOT RELY ON THE SERVICES FOR ANY LIFE SAFETY OR CRITICAL PURPOSES.
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
name: Tank Utility
provenance_date: '2026-11-10'
provider_name: Tank Utility
provider_slug: tank-utility
slug: tank-utility-eligibility
source_date: '2026-11-10'
source_filename: tank-utility-eligibility.yml
source_heading: Eligibility
source_page: https://tankutility.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tank Utility\naid: tank-utility\nurl: https://tankutility.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Products and Services are not available to all persons or in all countries; Sites are designed for Target\n    Countries where Tank Utility supports the Product.\nentity_types:\n- type: individual\n  text: You may use the Services only if you can form a binding contract with Tank Utility\nrestricted_uses:\n- summary: No life safety or critical uses\n  text: YOU AGREE THAT YOU WILL NOT RELY ON THE SERVICES FOR ANY LIFE SAFETY OR CRITICAL PURPOSES.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the Services by anyone under the age of 18 is strictly prohibited and is a violation\n    of these Terms.\n"
source_yaml_url: https://artifacts.apis.io/tank-utility/eligibility/tank-utility-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tank Utility's own page on 2026-11-10.
synthetic: false
tags:
- Propane
- Tank Monitoring
- IoT
- Fuel Delivery
- Telemetry
- Energy
- Sensors
- Company
---
