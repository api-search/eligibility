---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years or older to create an account.
    type: individual
  minimum_age:
    text: You must be 18 years or older to create an account.
    value: '18'
  restricted_uses:
  - summary: Restricted goods
    text: no sale of prescription drugs, controlled substances, or recalled products
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accounts are tied to a verified mobile phone number; one account per person.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: healthai-com
provenance_date: '2026-11-09'
provider_name: healthai-com
provider_slug: healthai-com
slug: healthai-com-eligibility
source_date: '2026-11-09'
source_filename: healthai-com-eligibility.yml
source_heading: Eligibility
source_page: https://app.healthai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: healthai-com\naid: healthai-com\nurl: https://app.healthai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years or older to create an account.\nrestricted_uses:\n- summary: Restricted goods\n  text: no sale of prescription drugs, controlled substances, or recalled products\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accounts are tied to a verified mobile phone number; one account per person.\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to create an account.\n"
source_yaml_url: https://artifacts.apis.io/healthai-com/eligibility/healthai-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from healthai-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Artificial Intelligence
- Evidence
- Tools
---
