---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site may not be appropriate or available for use in some jurisdictions outside of the United States. We reserve the right to limit Site availability to any geographic area.
  minimum_age:
    text: you are at least the age of legal majority in your place of residence and otherwise legally competent to enter into contracts
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
name: Machinify
provenance_date: '2026-11-10'
provider_name: Machinify
provider_slug: machinify
slug: machinify-eligibility
source_date: '2026-11-10'
source_filename: machinify-eligibility.yml
source_heading: Eligibility
source_page: https://www.machinify.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Machinify\naid: machinify\nurl: https://www.machinify.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site may not be appropriate or available for use in some jurisdictions outside of the United States.\n    We reserve the right to limit Site availability to any geographic area.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are at least the age of legal majority in your place of residence and otherwise legally competent to\n    enter into contracts\n"
source_yaml_url: https://artifacts.apis.io/machinify/eligibility/machinify-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Machinify's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Payment Integrity
- Health Insurance
- Artificial Intelligence
- Claims
- Subrogation
- Pharmacy
---
