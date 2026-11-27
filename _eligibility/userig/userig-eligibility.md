---
api_specs:
- filename: userig-openapi-generated.yml
  format: yaml
  label: Rig API
  slug: userig-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/userig/openapi/_ae-authored/userig-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Mesh pairing limited to owned machines
    text: UseRig may use a Network Extension (Packet Tunnel) only to connect to machines you own and have paired
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
name: Rig
provenance_date: '2026-11-10'
provider_name: Rig
provider_slug: userig
slug: userig-eligibility
source_date: '2026-11-10'
source_filename: userig-eligibility.yml
source_heading: Eligibility
source_page: https://userig.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rig\naid: userig\nurl: https://userig.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Mesh pairing limited to owned machines\n  text: UseRig may use a Network Extension (Packet Tunnel) only to connect to machines you own and have paired\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/userig/eligibility/userig-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Rig's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Development
- Mac
- Windows
- Process-Manager
---
