---
api_specs:
- filename: farmready-openapi-generated.yml
  format: yaml
  label: FarmReady (Bolt, Cart, Shed) API
  slug: farmready-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmready/openapi/_ae-authored/farmready-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
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
name: FarmReady (Bolt, Cart, Shed)
provenance_date: '2026-11-09'
provider_name: FarmReady (Bolt, Cart, Shed)
provider_slug: farmready
slug: farmready-eligibility
source_date: '2026-11-09'
source_filename: farmready-eligibility.yml
source_heading: Eligibility
source_page: https://www.farmready.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FarmReady (Bolt, Cart, Shed)\naid: farmready\nurl: https://www.farmready.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use\
  \ the Service.\n"
source_yaml_url: https://artifacts.apis.io/farmready/eligibility/farmready-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from FarmReady (Bolt, Cart, Shed)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Farm Management
- Inventory
- Equipment
- Safety
---
