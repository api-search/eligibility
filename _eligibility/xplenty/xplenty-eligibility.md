---
api_specs:
- filename: xplenty-openapi-generated.yml
  format: yaml
  label: Integrate.io API
  slug: xplenty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xplenty/openapi/_ae-authored/xplenty-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THESE TERMS.
    type: business
  - text: You are the age of majority in Your jurisdiction
    type: individual
  minimum_age:
    text: You are the age of majority in Your jurisdiction
    value: age of majority
  restricted_uses:
  - summary: Offensive or illegal use
    text: Integrate.io strictly prohibits the use of the Services or any of its functionalities for offensive, illegal or harming purposes.
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
name: Integrate.io
provenance_date: '2026-11-10'
provider_name: Integrate.io
provider_slug: xplenty
slug: xplenty-eligibility
source_date: '2026-11-10'
source_filename: xplenty-eligibility.yml
source_heading: Eligibility
source_page: https://www.integrate.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Integrate.io\naid: xplenty\nurl: https://www.integrate.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THESE TERMS.\n- type: individual\n  text: You are the age of majority in Your jurisdiction\nrestricted_uses:\n- summary: Offensive or illegal use\n  text: Integrate.io strictly prohibits the use of the Services or any of its functionalities for offensive, illegal\n    or\
  \ harming purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You are the age of majority in Your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/xplenty/eligibility/xplenty-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Integrate.io's own page on 2026-11-10.
synthetic: false
tags:
- Data Integration
- ETL
- Low-Code
- Artificial Intelligence
- Cloud
---
