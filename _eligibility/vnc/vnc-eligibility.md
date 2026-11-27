---
api_specs:
- filename: vnc-cloud-addresses-api-openapi.yml
  format: yaml
  label: VNC Cloud Addresses API
  slug: vnc-cloud-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vnc/openapi/vnc-cloud-addresses-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customers purchasing as individuals, who are classified as consumers under consumer rights regulations, have the right to withdraw from the purchase within fourteen working days of the day after the date the item is delivered.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embedding in third-party products
    text: RealVNC® is the only organization able to offer commercial licenses to embed remote control and access capability into third-party products and services.
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
name: VNC
provenance_date: '2026-11-10'
provider_name: VNC
provider_slug: vnc
slug: vnc-eligibility
source_date: '2026-11-10'
source_filename: vnc-eligibility.yml
source_heading: Eligibility
source_page: https://www.realvnc.com/en/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VNC\naid: vnc\nurl: https://www.realvnc.com/en/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Customers purchasing as individuals, who are classified as consumers under consumer rights regulations,\n    have the right to withdraw from the purchase within fourteen working days of the day after the date the item\n    is delivered.\nrestricted_uses:\n- summary: Embedding in third-party products\n  text: RealVNC® is the only organization able to offer commercial licenses to embed remote control and access capability\n    into third-party\
  \ products and services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vnc/eligibility/vnc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from VNC's own page on 2026-11-10.
synthetic: false
tags:
- Remote Desktop
- Remote Access
- VNC
- Networking
- Screen Sharing
---
