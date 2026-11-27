---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated decisions with significant effect
    text: User shall not engage in any automatic decision making (including, without limitation, profiling), or relied upon in isolation to make a decision, relating to any person, which has a legal effect or a similarly significant effect on that person.
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
name: Pecan
provenance_date: '2026-11-10'
provider_name: Pecan
provider_slug: pecan
slug: pecan-eligibility
source_date: '2026-11-10'
source_filename: pecan-eligibility.yml
source_heading: Eligibility
source_page: https://www.pecan.ai/license-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pecan\naid: pecan\nurl: https://www.pecan.ai/license-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Automated decisions with significant effect\n  text: User shall not engage in any automatic decision making (including, without limitation, profiling), or relied\n    upon in isolation to make a decision, relating to any person, which has a legal effect or a similarly significant\n    effect on that person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/pecan/eligibility/pecan-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Pecan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Predictive Analytics
- Machine Learning
- Data Science
- Forecasting
- Business Intelligence
---
