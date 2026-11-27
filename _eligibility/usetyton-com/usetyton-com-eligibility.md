---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16, able to enter a contract, and allowed to use the Service under the laws that apply to you.
    type: individual
  - text: If you use Tyton for an organization, you confirm that you are allowed to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 16, able to enter a contract
    value: '16'
  restricted_uses:
  - summary: Sending sensitive data
    text: Send passwords, payment card numbers, or special-category data
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
name: usetyton-com
provenance_date: '2026-11-10'
provider_name: usetyton-com
provider_slug: usetyton-com
slug: usetyton-com-eligibility
source_date: '2026-11-10'
source_filename: usetyton-com-eligibility.yml
source_heading: Eligibility
source_page: https://usetyton.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: usetyton-com\naid: usetyton-com\nurl: https://usetyton.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16, able to enter a contract, and allowed to use the Service under the laws that apply\n    to you.\n- type: business\n  text: If you use Tyton for an organization, you confirm that you are allowed to bind that organization.\nrestricted_uses:\n- summary: Sending sensitive data\n  text: Send passwords, payment card numbers, or special-category data\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16, able to enter a contract\n"
source_yaml_url: https://artifacts.apis.io/usetyton-com/eligibility/usetyton-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from usetyton-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Meta Pixel
- Conversions API
- Marketing
- Automation
---
