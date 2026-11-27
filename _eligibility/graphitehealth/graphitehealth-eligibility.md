---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Site for use only by persons located in the United States.
  entity_types:
  - text: solely for your own personal, noncommercial use
    type: individual
  - text: ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT)
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: solely for your own personal, noncommercial use
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
name: Graphite Health
provenance_date: '2026-11-09'
provider_name: Graphite Health
provider_slug: graphitehealth
slug: graphitehealth-eligibility
source_date: '2026-11-09'
source_filename: graphitehealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.graphitehealth.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Graphite Health\naid: graphitehealth\nurl: https://www.graphitehealth.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Site for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: solely for your own personal, noncommercial use\n- type: business\n  text: ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT)\nrestricted_uses:\n- summary: Commercial use\n  text: solely for your own personal, noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/graphitehealth/eligibility/graphitehealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Graphite Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Data
- Interoperability
- Clinical Data
- FHIR
- openEHR
- Data Standards
- Marketplace
- Non-Profit
- Digital Health
---
