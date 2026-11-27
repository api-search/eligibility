---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: F&G is not authorized to transact business outside of the United States
  minimum_age:
    text: The Website is not intended for children under the age of eighteen (18).
    value: '18'
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
name: FGL Holdings
provenance_date: '2026-11-09'
provider_name: FGL Holdings
provider_slug: fgl-holdings
slug: fgl-holdings-eligibility
source_date: '2026-11-09'
source_filename: fgl-holdings-eligibility.yml
source_heading: Eligibility
source_page: https://www.fglife.com/website-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FGL Holdings\naid: fgl-holdings\nurl: https://www.fglife.com/website-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: F&G is not authorized to transact business outside of the United States\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is not intended for children under the age of eighteen (18).\n"
source_yaml_url: https://artifacts.apis.io/fgl-holdings/eligibility/fgl-holdings-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from FGL Holdings's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Annuities
- Financial Services
- Life Insurance
- Retirement
- Pension-Risk-Transfer
---
