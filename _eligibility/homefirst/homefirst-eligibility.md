---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Minors or people below 18 years old are not allowed to use this Website or Mobile Applications.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: by providing your details including your KYC for enquiring or availing the loan facility from us, you authorise us to share such information with any credit information company
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HomeFirst
provenance_date: '2026-11-09'
provider_name: HomeFirst
provider_slug: homefirst
slug: homefirst-eligibility
source_date: '2026-11-09'
source_filename: homefirst-eligibility.yml
source_heading: Eligibility
source_page: https://homefirstindia.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HomeFirst\naid: homefirst\nurl: https://homefirstindia.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: by providing your details including your KYC for enquiring or availing the loan facility from us, you authorise\n    us to share such information with any credit information company\nminimum_age:\n  value: '18'\n  text: Minors or people below 18 years old are not allowed to use this Website or Mobile Applications.\n"
source_yaml_url: https://artifacts.apis.io/homefirst/eligibility/homefirst-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from HomeFirst's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Financial Services
- Housing Finance
- Home Loans
- Mortgage
- Lending
- India
- Fintech
---
