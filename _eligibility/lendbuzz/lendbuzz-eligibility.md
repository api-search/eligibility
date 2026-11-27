---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, organized under the laws of, or ordinarily resident in any country or territory subject to comprehensive sanctions administered by the United States government
  entity_types:
  - text: This Site is intended solely for users who are 18 years of age or older
    type: individual
  minimum_age:
    text: This Site is intended solely for users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: You agree to access and use the Site and any products or services offered through the Site for your personal, non-commercial use only
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to reject any registration and/or decline any application for a loan for any lawful purpose.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lendbuzz
provenance_date: '2026-11-09'
provider_name: Lendbuzz
provider_slug: lendbuzz
slug: lendbuzz-eligibility
source_date: '2026-11-09'
source_filename: lendbuzz-eligibility.yml
source_heading: Eligibility
source_page: https://www.lendbuzz.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lendbuzz\naid: lendbuzz\nurl: https://www.lendbuzz.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, organized under the laws of, or ordinarily resident in any country\n    or territory subject to comprehensive sanctions administered by the United States government\nentity_types:\n- type: individual\n  text: This Site is intended solely for users who are 18 years of age or older\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: You agree to access and use the Site and any products or services offered through\
  \ the Site for your personal,\n    non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to reject any registration and/or decline any application for a loan for any lawful\n    purpose.\nminimum_age:\n  value: '18'\n  text: This Site is intended solely for users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/lendbuzz/eligibility/lendbuzz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Lendbuzz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Auto Lending
- Automotive
- Financial Services
- Fintech
- Lending
- Credit
- Machine Learning
- Consumer Finance
- Dealers
---
