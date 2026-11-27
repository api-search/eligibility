---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Web site must only be used within the United States or other jurisdiction that recognizes these laws and these contractual provisions.
  entity_types:
  - text: We have created this Web site for individuals who are at least 13 years of age.
    type: individual
  minimum_age:
    text: We have created this Web site for individuals who are at least 13 years of age. Only the parent or legal guardian of a child under 13 can access our services
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: federal law requires that we obtain, verify, and record certain information about you to comply with our Customer Identification Program
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prosperity Bank
provenance_date: '2026-11-10'
provider_name: Prosperity Bank
provider_slug: prosperity-bank
slug: prosperity-bank-eligibility
source_date: '2026-11-10'
source_filename: prosperity-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.prosperitybankusa.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prosperity Bank\naid: prosperity-bank\nurl: https://www.prosperitybankusa.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Web site must only be used within the United States or other jurisdiction that recognizes these laws\n    and these contractual provisions.\nentity_types:\n- type: individual\n  text: We have created this Web site for individuals who are at least 13 years of age.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: federal law requires that we obtain, verify, and record certain information\
  \ about you to comply with our\n    Customer Identification Program\nminimum_age:\n  value: '13'\n  text: We have created this Web site for individuals who are at least 13 years of age. Only the parent or legal\n    guardian of a child under 13 can access our services\n"
source_yaml_url: https://artifacts.apis.io/prosperity-bank/eligibility/prosperity-bank-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Prosperity Bank's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Regional Bank
- Texas
- Open Finance
---
