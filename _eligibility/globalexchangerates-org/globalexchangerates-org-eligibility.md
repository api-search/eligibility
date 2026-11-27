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
  - summary: Informational use only
    text: The data is provided for informational purposes only and does not constitute financial, accounting, tax, legal, or investment advice.
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
name: globalexchangerates-org
provenance_date: '2026-11-09'
provider_name: globalexchangerates-org
provider_slug: globalexchangerates-org
slug: globalexchangerates-org-eligibility
source_date: '2026-11-09'
source_filename: globalexchangerates-org-eligibility.yml
source_heading: Eligibility
source_page: https://www.globalexchangerates.org/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: globalexchangerates-org\naid: globalexchangerates-org\nurl: https://www.globalexchangerates.org/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Informational use only\n  text: The data is provided for informational purposes only and does not constitute financial, accounting, tax,\n    legal, or investment advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/globalexchangerates-org/eligibility/globalexchangerates-org-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from globalexchangerates-org's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Exchange Rates
- ERP
---
