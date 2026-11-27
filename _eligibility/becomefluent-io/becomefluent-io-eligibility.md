---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Fluent Teams on the web is billed per seat through Stripe, to the workspace admin who buys it.
    type: business
  minimum_age:
    text: You must be at least 16 years of age to use Fluent.
    value: '16'
  restricted_uses:
  - summary: Recording without consent
    text: Record conversations without the knowledge or consent of participants where required by applicable law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use Fluent, you must create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fluent
provenance_date: '2026-11-09'
provider_name: Fluent
provider_slug: becomefluent-io
slug: becomefluent-io-eligibility
source_date: '2026-11-09'
source_filename: becomefluent-io-eligibility.yml
source_heading: Eligibility
source_page: https://becomefluent.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fluent\naid: becomefluent-io\nurl: https://becomefluent.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Fluent Teams on the web is billed per seat through Stripe, to the workspace admin who buys it.\nrestricted_uses:\n- summary: Recording without consent\n  text: Record conversations without the knowledge or consent of participants where required by applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use Fluent, you must create an account.\nminimum_age:\n  value: '16'\n  text: You\
  \ must be at least 16 years of age to use Fluent.\n"
source_yaml_url: https://artifacts.apis.io/becomefluent-io/eligibility/becomefluent-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Fluent's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Productivity
- Meeting Notes
- Mobile App
- Encryption
---
