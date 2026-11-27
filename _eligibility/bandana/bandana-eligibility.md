---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Country refers to: United States'
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
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
name: Bandana
provenance_date: '2026-11-09'
provider_name: Bandana
provider_slug: bandana
slug: bandana-eligibility
source_date: '2026-11-09'
source_filename: bandana-eligibility.yml
source_heading: Eligibility
source_page: https://bandana.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bandana\naid: bandana\nurl: https://bandana.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Country refers to: United States'\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use\
  \ the Service.\n"
source_yaml_url: https://artifacts.apis.io/bandana/eligibility/bandana-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Bandana's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Job
- Hiring
- Recruiting
- Hourly Workers
- Employment
- Careers
---
