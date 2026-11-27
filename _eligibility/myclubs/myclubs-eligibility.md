---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users may only register in their own name. They must be of legal age and a natural person.
    type: individual
  minimum_age:
    text: They must be of legal age and a natural person.
    value: null
  restricted_uses:
  - summary: Prohibited content in reviews/posts
    text: If the member evaluates sports offers and sports providers, they must refrain from posting content that constitutes a criminal offense or an administrative offense
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: myClubs reserves the right to refuse registration of users without giving reasons.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Myclubs
provenance_date: '2026-11-10'
provider_name: Myclubs
provider_slug: myclubs
slug: myclubs-eligibility
source_date: '2026-11-10'
source_filename: myclubs-eligibility.yml
source_heading: Eligibility
source_page: https://www.myclubs.com/at/en/general-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Myclubs\naid: myclubs\nurl: https://www.myclubs.com/at/en/general-terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users may only register in their own name. They must be of legal age and a natural person.\nrestricted_uses:\n- summary: Prohibited content in reviews/posts\n  text: If the member evaluates sports offers and sports providers, they must refrain from posting content that\n    constitutes a criminal offense or an administrative offense\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n\
  \  text: myClubs reserves the right to refuse registration of users without giving reasons.\nminimum_age:\n  value: null\n  text: They must be of legal age and a natural person.\n"
source_yaml_url: https://artifacts.apis.io/myclubs/eligibility/myclubs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Myclubs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fitness
- Sports
- Membership
- Wellness
- Corporate Fitness
- Health
- Subscription
---
