---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not be located in, organised under the laws of, or ordinarily resident in a Sanctioned Country
  entity_types:
  - text: Customer means the entity entering into this Agreement with the Supplier as identified in the Order Form.
    type: business
  - text: Consumer means a natural person who enters into this Agreement primarily for purposes outside that person's trade, business, craft or profession.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited AI practices
    text: the Customer shall not use the Service for any Prohibited Practices under the AI Regulation
  - summary: Military purposes
    text: nor use or offer the Service for military purposes, including but not limited to the development, production, testing or use of weapons
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
name: Avrea
provenance_date: '2026-11-09'
provider_name: Avrea
provider_slug: avrea
slug: avrea-eligibility
source_date: '2026-11-09'
source_filename: avrea-eligibility.yml
source_heading: Eligibility
source_page: https://avrea.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avrea\naid: avrea\nurl: https://avrea.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not be located in, organised under the laws of, or ordinarily resident in a Sanctioned Country\nentity_types:\n- type: business\n  text: Customer means the entity entering into this Agreement with the Supplier as identified in the Order Form.\n- type: individual\n  text: Consumer means a natural person who enters into this Agreement primarily for purposes outside that person's\n    trade, business, craft or profession.\nrestricted_uses:\n- summary: Prohibited\
  \ AI practices\n  text: the Customer shall not use the Service for any Prohibited Practices under the AI Regulation\n- summary: Military purposes\n  text: nor use or offer the Service for military purposes, including but not limited to the development, production,\n    testing or use of weapons\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avrea/eligibility/avrea-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Avrea's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CI/CD
- Continuous Integration
- GitHub Actions
- Build Infrastructure
- Runners
- Caching
- Observability
- DevOps
- Developer Tools
---
