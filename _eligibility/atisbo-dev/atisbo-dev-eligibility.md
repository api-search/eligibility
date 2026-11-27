---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Atisbo is for organisational use
    type: business
  - text: requires you to be at least 18
    type: individual
  minimum_age:
    text: requires you to be at least 18
    value: '18'
  restricted_uses:
  - summary: Special categories of personal data
    text: special categories of personal data — health records, biometrics, government identifiers — without agreeing it with us first
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
name: atisbo-dev
provenance_date: '2026-11-09'
provider_name: atisbo-dev
provider_slug: atisbo-dev
slug: atisbo-dev-eligibility
source_date: '2026-11-09'
source_filename: atisbo-dev-eligibility.yml
source_heading: Eligibility
source_page: https://app.atisbo.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: atisbo-dev\naid: atisbo-dev\nurl: https://app.atisbo.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Atisbo is for organisational use\n- type: individual\n  text: requires you to be at least 18\nrestricted_uses:\n- summary: Special categories of personal data\n  text: special categories of personal data — health records, biometrics, government identifiers — without agreeing\n    it with us first\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: requires you\
  \ to be at least 18\n"
source_yaml_url: https://artifacts.apis.io/atisbo-dev/eligibility/atisbo-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from atisbo-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Product Management
- Evidence
- Decision Support
- Artificial Intelligence
---
