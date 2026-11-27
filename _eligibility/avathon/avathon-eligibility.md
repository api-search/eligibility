---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service, as applicable.
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Sanctioned or restricted parties and locations
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a "terrorist supporting" country, and (ii) You are not listed on any United States government list of prohibited or restricted parties.
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
name: Avathon
provenance_date: '2026-11-09'
provider_name: Avathon
provider_slug: avathon
slug: avathon-eligibility
source_date: '2026-11-09'
source_filename: avathon-eligibility.yml
source_heading: Eligibility
source_page: https://avathon.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avathon\naid: avathon\nurl: https://avathon.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service, as applicable.\nrestricted_uses:\n- summary: Sanctioned or restricted parties and locations\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo, or that has been designated\
  \ by the United States government as a \"terrorist supporting\"\n    country, and (ii) You are not listed on any United States government list of prohibited or restricted parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/avathon/eligibility/avathon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Avathon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Industrial AI
- Predictive Maintenance
- Asset Performance Management
- Computer Vision
- Digital Twin
- Renewable Energy
- Oil and Gas
- Manufacturing
- Aerospace and Defense
- Logistics
---
