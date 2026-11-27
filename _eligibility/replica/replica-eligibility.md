---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Site only if you are 18 years of age or older and can form a binding contract with Replica
    type: individual
  - text: If you use the Site on behalf of an entity or another individual, you represent and warrant that you have the authority to bind that entity or individual
    type: business
  minimum_age:
    text: You may use the Site only if you are 18 years of age or older and can form a binding contract with Replica
    value: '18'
  restricted_uses:
  - summary: Illegal or improper purposes
    text: you shall not use the Site for any illegal, unauthorized or other improper purposes
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
name: Replica
provenance_date: '2026-11-10'
provider_name: Replica
provider_slug: replica
slug: replica-eligibility
source_date: '2026-11-10'
source_filename: replica-eligibility.yml
source_heading: Eligibility
source_page: https://replicahq.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Replica\naid: replica\nurl: https://replicahq.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Site only if you are 18 years of age or older and can form a binding contract with Replica\n- type: business\n  text: If you use the Site on behalf of an entity or another individual, you represent and warrant that you have\n    the authority to bind that entity or individual\nrestricted_uses:\n- summary: Illegal or improper purposes\n  text: you shall not use the Site for any illegal, unauthorized or other\
  \ improper purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Site only if you are 18 years of age or older and can form a binding contract with Replica\n"
source_yaml_url: https://artifacts.apis.io/replica/eligibility/replica-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Replica's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Mobility
- Transportation
- Geospatial
- Urban Planning
- Travel Demand Modeling
- Government
- Analytics
- Data Platform
---
