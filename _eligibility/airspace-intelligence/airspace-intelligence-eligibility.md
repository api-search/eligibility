---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The individual or entity that is visiting the Site or otherwise interacting with us.
    type: individual
  - text: You may only use such User ID while you are employed by the company for which ASI authorized your access to the Service.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Security violations
    text: Users are prohibited from violating or attempting to violate the security of the site.
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
name: Airspace Intelligence
provenance_date: '2026-11-09'
provider_name: Airspace Intelligence
provider_slug: airspace-intelligence
slug: airspace-intelligence-eligibility
source_date: '2026-11-09'
source_filename: airspace-intelligence-eligibility.yml
source_heading: Eligibility
source_page: https://www.asi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airspace Intelligence\naid: airspace-intelligence\nurl: https://www.asi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The individual or entity that is visiting the Site or otherwise interacting with us.\n- type: business\n  text: You may only use such User ID while you are employed by the company for which ASI authorized your access\n    to the Service.\nrestricted_uses:\n- summary: Security violations\n  text: Users are prohibited from violating or attempting to violate the security of the site.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airspace-intelligence/eligibility/airspace-intelligence-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Airspace Intelligence's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Aviation
- Air Traffic Management
- Defense
- Logistics
- Optimization
- Energy
- Aerospace
---
