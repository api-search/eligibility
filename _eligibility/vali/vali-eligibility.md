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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As part of the registration process, Customer will identify an administrative username and password for Customer’s Company account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vali
provenance_date: '2026-11-10'
provider_name: Vali
provider_slug: vali
slug: vali-eligibility
source_date: '2026-11-10'
source_filename: vali-eligibility.yml
source_heading: Eligibility
source_page: https://vali.health/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vali\naid: vali\nurl: https://vali.health/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As part of the registration process, Customer will identify an administrative username and password for\n    Customer’s Company account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vali/eligibility/vali-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Vali's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Home Care
- Healthcare
- Workforce
---
