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
    kyc: true
    text: (ii) “know your client” and compliance checks and (iii) any sanctions check run by VAT IT
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: VAT IT
provenance_date: '2026-11-10'
provider_name: VAT IT
provider_slug: vat-it
slug: vat-it-eligibility
source_date: '2026-11-10'
source_filename: vat-it-eligibility.yml
source_heading: Eligibility
source_page: https://vatit.com/vat-it-compliance-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VAT IT\naid: vat-it\nurl: https://vatit.com/vat-it-compliance-terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: (ii) “know your client” and compliance checks and (iii) any sanctions check run by VAT IT\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vat-it/eligibility/vat-it-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from VAT IT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tax
- Compliance
- Artificial Intelligence
- Finance
- Software-as-a-Service
---
