---
api_specs:
- filename: teejlab-openapi-generated.yml
  format: yaml
  label: TeejLab API
  slug: teejlab-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teejlab/openapi/_ae-authored/teejlab-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: make TeejLab’s Products and/or Services available to you as one living person (“ Individual ”)
    type: individual
  - text: if you are accessing and using the TeejLab Services on behalf of a company (such as your employer) or other legal entity
    type: business
  - text: make TeejLab’s Products and/or Services available to you as a group of equal to or more than 10 but less than 500 living persons that are currently affiliated with accredited academic institute(s) as students and/or staff (“ Academic ”)
    type: nonprofit
  minimum_age:
    text: null
    value: null
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
name: TeejLab
provenance_date: '2026-11-10'
provider_name: TeejLab
provider_slug: teejlab
slug: teejlab-eligibility
source_date: '2026-11-10'
source_filename: teejlab-eligibility.yml
source_heading: Eligibility
source_page: https://teejlab.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TeejLab\naid: teejlab\nurl: https://teejlab.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: make TeejLab’s Products and/or Services available to you as one living person (“ Individual ”)\n- type: business\n  text: if you are accessing and using the TeejLab Services on behalf of a company (such as your employer) or other\n    legal entity\n- type: nonprofit\n  text: make TeejLab’s Products and/or Services available to you as a group of equal to or more than 10 but less\n    than 500 living persons that are currently affiliated\
  \ with accredited academic institute(s) as students and/or\n    staff (“ Academic ”)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/teejlab/eligibility/teejlab-eligibility.yml
stated_fields:
- entity_types
summary_line: 3 quoted statements, read from TeejLab's own page on 2026-11-10.
synthetic: false
tags:
- API Discovery
- API Security
- API Governance
- API Marketplace
- API Monetization
- DevSecOps
- Compliance
---
