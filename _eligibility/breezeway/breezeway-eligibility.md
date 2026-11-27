---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you warrant to Breezeway that you are at least 18 years of age and legally competent to agree to this Agreement
    type: individual
  - text: Breezeway shall consider the Service under this Agreement to be for your business use
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No commercial purpose use
    text: (i) use the Service or its contents for any commercial purpose
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
name: Breezeway
provenance_date: '2026-11-09'
provider_name: Breezeway
provider_slug: breezeway
slug: breezeway-eligibility
source_date: '2026-11-09'
source_filename: breezeway-eligibility.yml
source_heading: Eligibility
source_page: https://www.breezeway.io/terms?hsLang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Breezeway\naid: breezeway\nurl: https://www.breezeway.io/terms?hsLang=en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you warrant to Breezeway that you are at least 18 years of age and legally competent to agree to this Agreement\n- type: business\n  text: Breezeway shall consider the Service under this Agreement to be for your business use\nrestricted_uses:\n- summary: No commercial purpose use\n  text: (i) use the Service or its contents for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/breezeway/eligibility/breezeway-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Breezeway's own page on 2026-11-09.
synthetic: false
tags:
- Property Management
- Software-as-a-Service
- Operations Automation
- Guest Experience
- Real Estate
---
