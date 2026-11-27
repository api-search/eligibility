---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Airwave is for use by businesses and their authorized employees, contractors, and representatives.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Smart glasses recording responsibility
    text: You are responsible for following applicable laws, workplace policies, and safety rules when using the product.
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
name: Airwave
provenance_date: '2026-11-09'
provider_name: Airwave
provider_slug: airwave
slug: airwave-eligibility
source_date: '2026-11-09'
source_filename: airwave-eligibility.yml
source_heading: Eligibility
source_page: https://www.airwave.us/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airwave\naid: airwave\nurl: https://www.airwave.us/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Airwave is for use by businesses and their authorized employees, contractors, and representatives.\nrestricted_uses:\n- summary: Smart glasses recording responsibility\n  text: You are responsible for following applicable laws, workplace policies, and safety rules when using the product.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airwave/eligibility/airwave-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Airwave's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Field Service Management
- Smart Glasses
- Wearables
- Computer Vision
- Industrial
- AI Assistant
- Inspection Reports
- Safety
---
