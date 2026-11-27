---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Individuals who access or use our Website or any Materials, in any manner, must be 13 years of age or older (or the age of majority where you live).
    type: individual
  - text: If you are a business or organization that uses any of our products subject to a separate written agreement with us, your use of such products described in such agreement will be subject to that agreement.
    type: business
  minimum_age:
    text: must be 13 years of age or older (or the age of majority where you live)
    value: '13'
  restricted_uses:
  - summary: Consumer Data not for HR or competitor staff
    text: you are not a human resource specialist, researcher, manager, employee or contractor of a Payscale competitor
  - summary: Consumer Data not for commercial or litigation use
    text: you will not use the Consumer Data for commercial or litigation purposes
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
name: PayScale
provenance_date: '2026-11-10'
provider_name: PayScale
provider_slug: payscale
slug: payscale-eligibility
source_date: '2026-11-10'
source_filename: payscale-eligibility.yml
source_heading: Eligibility
source_page: https://www.payscale.com/about/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayScale\naid: payscale\nurl: https://www.payscale.com/about/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Individuals who access or use our Website or any Materials, in any manner, must be 13 years of age or older\n    (or the age of majority where you live).\n- type: business\n  text: If you are a business or organization that uses any of our products subject to a separate written agreement\n    with us, your use of such products described in such agreement will be subject to that agreement.\nrestricted_uses:\n- summary:\
  \ Consumer Data not for HR or competitor staff\n  text: you are not a human resource specialist, researcher, manager, employee or contractor of a Payscale competitor\n- summary: Consumer Data not for commercial or litigation use\n  text: you will not use the Consumer Data for commercial or litigation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: must be 13 years of age or older (or the age of majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/payscale/eligibility/payscale-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from PayScale's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compensation
- Salary Data
- Human Resources
- Benchmarking
- Pay Equity
- Compensation Management
- Workforce Data
---
