---
api_specs:
- filename: workspot-apis-api-openapi.yml
  format: yaml
  label: Workspot APIs API
  slug: workspot-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workspot/openapi/workspot-apis-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the company identified on the signature page below or on the corresponding Order
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Use prohibited
    text: Customer is expressly prohibited from using Purchased Services in any application or situation where use or failure could lead to death or serious bodily injury of any person
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
name: Workspot
provenance_date: '2026-11-10'
provider_name: Workspot
provider_slug: workspot
slug: workspot-eligibility
source_date: '2026-11-10'
source_filename: workspot-eligibility.yml
source_heading: Eligibility
source_page: https://www.workspot.com/legal/workspot-enterprise-subscription-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workspot\naid: workspot\nurl: https://www.workspot.com/legal/workspot-enterprise-subscription-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the company identified on the signature page below or on the corresponding Order\nrestricted_uses:\n- summary: High Risk Use prohibited\n  text: Customer is expressly prohibited from using Purchased Services in any application or situation where use\n    or failure could lead to death or serious bodily injury of any person\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/workspot/eligibility/workspot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Workspot's own page on 2026-11-10.
synthetic: false
tags:
- Virtual Desktop Infrastructure
- Desktop as a Service
- Cloud PC
- End User Computing
- Cloud Infrastructure
- Enterprise IT
- Workspace Management
- Software-as-a-Service
---
