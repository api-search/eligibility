---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity that has executed an Order Form (as defined below) that references and incorporates these Terms by reference (“ Customer ”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for time-critical or mission-critical use
    text: the Pocus Platform will not be used, and are not licensed for use, in connection with any time-critical or mission-critical functions.
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
name: Pocus
provenance_date: '2026-11-10'
provider_name: Pocus
provider_slug: pocus
slug: pocus-eligibility
source_date: '2026-11-10'
source_filename: pocus-eligibility.yml
source_heading: Eligibility
source_page: https://www.pocus.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pocus\naid: pocus\nurl: https://www.pocus.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity that has executed an Order Form (as defined below) that references and incorporates these Terms\n    by reference (“ Customer ”)\nrestricted_uses:\n- summary: Not for time-critical or mission-critical use\n  text: the Pocus Platform will not be used, and are not licensed for use, in connection with any time-critical\n    or mission-critical functions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pocus/eligibility/pocus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Pocus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales Intelligence
- Product-Led Sales
- Revenue Operations
- Go-To-Market
- Data Enrichment
- CRM
- Artificial Intelligence
- GraphQL
---
