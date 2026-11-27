---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services can be accessed from countries around the world and may contain references to Services that are not available in your country.
  entity_types:
  - text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH ALSO
    type: individual
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH ALSO
    value: legal age
  restricted_uses:
  - summary: Hazardous or safety-critical use of apps
    text: use the Also Apps in, or in association with, the design, construction, maintenance, or operation of any hazardous environments or systems, including any power generation systems
  - summary: No app use while driving
    text: Do not interact with the Also Apps while operating any vehicle, bicycle, scooter, motorcycle, other transportation device, or any activity which requires your full attention.
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
name: Also
provenance_date: '2026-11-09'
provider_name: Also
provider_slug: also
slug: also-eligibility
source_date: '2026-11-09'
source_filename: also-eligibility.yml
source_heading: Eligibility
source_page: https://ridealso.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Also\naid: also\nurl: https://ridealso.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services can be accessed from countries around the world and may contain references to Services that\n    are not available in your country.\nentity_types:\n- type: individual\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH ALSO\nrestricted_uses:\n- summary: Hazardous or safety-critical use of apps\n  text: use the Also Apps in, or in association with, the design, construction, maintenance, or operation of any\n    hazardous environments or systems,\
  \ including any power generation systems\n- summary: No app use while driving\n  text: Do not interact with the Also Apps while operating any vehicle, bicycle, scooter, motorcycle, other transportation\n    device, or any activity which requires your full attention.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH ALSO\n"
source_yaml_url: https://artifacts.apis.io/also/eligibility/also-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Also's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Micromobility
- Electric Vehicles
- Transportation
- E-Commerce
- Consumer Hardware
- Agentic Commerce
- Logistics
- Delivery
---
