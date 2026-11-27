---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all products and services are available in all states.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Federal Law requires that Northwestern Mutual obtain, verify and record information that identifies each owner.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Northwestern Mutual
provenance_date: '2026-11-10'
provider_name: Northwestern Mutual
provider_slug: northwestern-mutual
slug: northwestern-mutual-eligibility
source_date: '2026-11-10'
source_filename: northwestern-mutual-eligibility.yml
source_heading: Eligibility
source_page: https://www.northwesternmutual.com/legal-information/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Northwestern Mutual\naid: northwestern-mutual\nurl: https://www.northwesternmutual.com/legal-information/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not all products and services are available in all states.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Federal Law requires that Northwestern Mutual obtain, verify and record information that identifies each\n    owner.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/northwestern-mutual/eligibility/northwestern-mutual-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Northwestern Mutual's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Life Insurance
- Financial Services
- Wealth Management
- Annuities
- Investment Management
- Fortune 500
---
