---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all of the products or services described on the Site are available in all geographic areas. We make no claims that the Services or the Content are accessible or appropriate outside of the United States.
  entity_types:
  - text: AFFIRM THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE YOU RESIDE)
    type: individual
  minimum_age:
    text: AFFIRM THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE YOU RESIDE)
    value: '18'
  restricted_uses:
  - summary: Unlawful or out-of-scope use
    text: access or use the Services or Content for any unlawful purpose or otherwise beyond the scope of the rights granted herein
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
name: Alpine Bank
provenance_date: '2026-11-09'
provider_name: Alpine Bank
provider_slug: alpine-bank
slug: alpine-bank-eligibility
source_date: '2026-11-09'
source_filename: alpine-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.alpinebank.com/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alpine Bank\naid: alpine-bank\nurl: https://www.alpinebank.com/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not all of the products or services described on the Site are available in all geographic areas. We make\n    no claims that the Services or the Content are accessible or appropriate outside of the United States.\nentity_types:\n- type: individual\n  text: AFFIRM THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE\n    YOU RESIDE)\nrestricted_uses:\n- summary: Unlawful or out-of-scope use\n  text: access\
  \ or use the Services or Content for any unlawful purpose or otherwise beyond the scope of the rights\n    granted herein\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: AFFIRM THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE\n    YOU RESIDE)\n"
source_yaml_url: https://artifacts.apis.io/alpine-bank/eligibility/alpine-bank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Alpine Bank's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Financial Services
- Colorado
- Community
---
