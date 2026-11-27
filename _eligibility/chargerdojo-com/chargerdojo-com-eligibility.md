---
api_specs:
- filename: chargerdojo-com-openapi-generated.yml
  format: yaml
  label: ChargerDojo API
  slug: chargerdojo-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chargerdojo-com/openapi/_ae-authored/chargerdojo-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of a company, you are confirming you may bind that company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only systems you own or have permission to test
    text: only aim it at systems you own, operate, or have documented permission to test.
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
name: ChargerDojo
provenance_date: '2026-11-09'
provider_name: ChargerDojo
provider_slug: chargerdojo-com
slug: chargerdojo-com-eligibility
source_date: '2026-11-09'
source_filename: chargerdojo-com-eligibility.yml
source_heading: Eligibility
source_page: https://chargerdojo.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChargerDojo\naid: chargerdojo-com\nurl: https://chargerdojo.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of a company, you are confirming you may bind that company.\nrestricted_uses:\n- summary: Only systems you own or have permission to test\n  text: only aim it at systems you own, operate, or have documented permission to test.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chargerdojo-com/eligibility/chargerdojo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ChargerDojo's own page on 2026-11-09.
synthetic: false
tags:
- Electric Vehicles
- OCPI
- Testing
- Simulator
- Charging
---
