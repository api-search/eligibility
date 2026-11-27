---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  - text: Entities that have executed enterprise agreements with Pano (each, an “Enterprise”
    type: business
  minimum_age:
    text: if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services
    value: '13'
  restricted_uses:
  - summary: Children under 13
    text: if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services
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
name: Pano
provenance_date: '2026-11-10'
provider_name: Pano
provider_slug: pano
slug: pano-eligibility
source_date: '2026-11-10'
source_filename: pano-eligibility.yml
source_heading: Eligibility
source_page: https://www.pano.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pano\naid: pano\nurl: https://www.pano.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n- type: business\n  text: Entities that have executed enterprise agreements with Pano (each, an “Enterprise”\nrestricted_uses:\n- summary: Children under 13\n  text: if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services\n"
source_yaml_url: https://artifacts.apis.io/pano/eligibility/pano-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pano's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wildfire Detection
- Fire Detection
- Situational Awareness
- Geospatial
- Computer Vision
- Artificial Intelligence
- Emergency Management
- Public Safety
---
