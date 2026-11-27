---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Shaip does not collect any payments, fees, or charges from crowd workers, contributors, freelancers, or any individuals performing services on its platform (“Contributors”).
    type: individual
  - text: If you are a customer purchasing services from Shaip (for example, enterprise data services or subscriptions), any refund rights are governed exclusively by the applicable Master Services Agreement, Statement of Work, or other contractual arrangement
    type: business
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
name: Shaip
provenance_date: '2026-11-10'
provider_name: Shaip
provider_slug: shaip
slug: shaip-eligibility
source_date: '2026-11-10'
source_filename: shaip-eligibility.yml
source_heading: Eligibility
source_page: https://www.shaip.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shaip\naid: shaip\nurl: https://www.shaip.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Shaip does not collect any payments, fees, or charges from crowd workers, contributors, freelancers, or\n    any individuals performing services on its platform (“Contributors”).\n- type: business\n  text: If you are a customer purchasing services from Shaip (for example, enterprise data services or subscriptions),\n    any refund rights are governed exclusively by the applicable Master Services Agreement, Statement of Work,\
  \ or\n    other contractual arrangement\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shaip/eligibility/shaip-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Shaip's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data Annotation
- Machine Learning
- Platform
---
