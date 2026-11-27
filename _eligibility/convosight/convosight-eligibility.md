---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer must use the Services only where lawfully available and in compliance with applicable laws, including trade, sanctions and export-control laws.
  entity_types:
  - text: The Services are intended for organisations and professional or business use
    type: business
  minimum_age:
    text: may only be used by individuals who are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sole basis for individual decisions
    text: Outputs are not legal, financial, medical, employment, credit, insurance or other regulated advice and must not be used as the sole basis for decisions producing legal or similarly significant effects about an individual.
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
name: Convosight
provenance_date: '2026-11-09'
provider_name: Convosight
provider_slug: convosight
slug: convosight-eligibility
source_date: '2026-11-09'
source_filename: convosight-eligibility.yml
source_heading: Eligibility
source_page: https://www.convosight.com/policies/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Convosight\naid: convosight\nurl: https://www.convosight.com/policies/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer must use the Services only where lawfully available and in compliance with applicable laws, including\n    trade, sanctions and export-control laws.\nentity_types:\n- type: business\n  text: The Services are intended for organisations and professional or business use\nrestricted_uses:\n- summary: Sole basis for individual decisions\n  text: Outputs are not legal, financial, medical, employment, credit, insurance or other regulated advice and must\n  \
  \  not be used as the sole basis for decisions producing legal or similarly significant effects about an individual.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: may only be used by individuals who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/convosight/eligibility/convosight-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Convosight's own page on 2026-11-09.
synthetic: false
tags:
- Social Intelligence
- Video Analytics
- Consumer Insights
- Market Research
- Brand Analytics
- Multilingual Intelligence
---
