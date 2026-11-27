---
api_specs:
- filename: 3dpack-ing-packing-api-openapi.yml
  format: yaml
  label: 3dpack-ing Packing API
  slug: 3dpack-ing-packing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3dpack-ing/openapi/3dpack-ing-packing-api-openapi.yml
- filename: 3dpack-ing-typed-api-openapi.yml
  format: yaml
  label: 3dpack-ing Typed API
  slug: 3dpack-ing-typed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3dpack-ing/openapi/3dpack-ing-typed-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is operated by Novian Works, an individually owned business (ENK) registered in Norway.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: You agree not to use the Service for any unlawful purpose or in any way that could damage, disable, overburden, or impair the Service.
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
name: 3dpack-ing
provenance_date: '2026-11-09'
provider_name: 3dpack-ing
provider_slug: 3dpack-ing
slug: 3dpack-ing-eligibility
source_date: '2026-11-09'
source_filename: 3dpack-ing-eligibility.yml
source_heading: Eligibility
source_page: https://3dpack.ing/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 3dpack-ing\naid: 3dpack-ing\nurl: https://3dpack.ing/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is operated by Novian Works, an individually owned business (ENK) registered in Norway.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You agree not to use the Service for any unlawful purpose or in any way that could damage, disable, overburden,\n    or impair the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/3dpack-ing/eligibility/3dpack-ing-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from 3dpack-ing's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- 3D
- Software-as-a-Service
---
