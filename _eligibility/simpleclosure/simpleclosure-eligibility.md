---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Referral Program: Each Referrer must be at least 18 years old and a resident of the United States of America.'
  entity_types:
  - text: If you wish to use the Services, you must be at least 18 years old (or the age of majority in your state, province, or country).
    type: individual
  - text: 'IF YOU ARE ACCEPTING THESE TERMS ON BEHALF OF YOUR EMPLOYER OR ANOTHER ENTITY, YOU REPRESENT AND WARRANT THAT: (I) YOU HAVE FULL LEGAL AUTHORITY TO BIND THE APPLICABLE ENTITY TO THESE TERMS;'
    type: business
  minimum_age:
    text: If you wish to use the Services, you must be at least 18 years old (or the age of majority in your state, province, or country).
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
name: Simpleclosure
provenance_date: '2026-11-10'
provider_name: Simpleclosure
provider_slug: simpleclosure
slug: simpleclosure-eligibility
source_date: '2026-11-10'
source_filename: simpleclosure-eligibility.yml
source_heading: Eligibility
source_page: https://simpleclosure.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Simpleclosure\naid: simpleclosure\nurl: https://simpleclosure.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Referral Program: Each Referrer must be at least 18 years old and a resident of the United States of America.'\nentity_types:\n- type: individual\n  text: If you wish to use the Services, you must be at least 18 years old (or the age of majority in your state,\n    province, or country).\n- type: business\n  text: 'IF YOU ARE ACCEPTING THESE TERMS ON BEHALF OF YOUR EMPLOYER OR ANOTHER ENTITY, YOU REPRESENT AND WARRANT\n    THAT: (I) YOU HAVE FULL LEGAL AUTHORITY\
  \ TO BIND THE APPLICABLE ENTITY TO THESE TERMS;'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you wish to use the Services, you must be at least 18 years old (or the age of majority in your state,\n    province, or country).\n"
source_yaml_url: https://artifacts.apis.io/simpleclosure/eligibility/simpleclosure-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Simpleclosure's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Dissolution
- Startup Shutdown
- Wind Down
- Legal Tech
- Fintech
- Compliance
---
