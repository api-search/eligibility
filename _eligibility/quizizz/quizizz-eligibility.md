---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Accounts are for individuals only and sharing accounts with multiple people, including people at the same organization is strictly forbidden
    type: individual
  minimum_age:
    text: The Service is for users of all ages. For children younger than 13, Wayground offers a limited feature set and does not require Wayground to obtain parental consent.
    value: null
  restricted_uses:
  - summary: Void where prohibited
    text: Use of the Service is void where prohibited.
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
name: Wayground
provenance_date: '2026-11-10'
provider_name: Wayground
provider_slug: quizizz
slug: quizizz-eligibility
source_date: '2026-11-10'
source_filename: quizizz-eligibility.yml
source_heading: Eligibility
source_page: https://wayground.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wayground\naid: quizizz\nurl: https://wayground.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Accounts are for individuals only and sharing accounts with multiple people, including people at the same\n    organization is strictly forbidden\nrestricted_uses:\n- summary: Void where prohibited\n  text: Use of the Service is void where prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The Service is for users of all ages. For children younger than\
  \ 13, Wayground offers a limited feature set\n    and does not require Wayground to obtain parental consent.\n"
source_yaml_url: https://artifacts.apis.io/quizizz/eligibility/quizizz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Wayground's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- K-12
- Learning
- Assessment
- Artificial Intelligence
- MCP
- LTI
- Rostering
- SSO
---
