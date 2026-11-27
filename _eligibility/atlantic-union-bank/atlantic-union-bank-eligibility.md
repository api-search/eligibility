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
    text: When you open an account, we will ask for your name, address, date of birth, and other information that will allow us to identify you.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atlantic Union Bank
provenance_date: '2026-11-09'
provider_name: Atlantic Union Bank
provider_slug: atlantic-union-bank
slug: atlantic-union-bank-eligibility
source_date: '2026-11-09'
source_filename: atlantic-union-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.atlanticunionbank.com/about/helpful-links/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlantic Union Bank\naid: atlantic-union-bank\nurl: https://www.atlanticunionbank.com/about/helpful-links/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: When you open an account, we will ask for your name, address, date of birth, and other information that\n    will allow us to identify you.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/atlantic-union-bank/eligibility/atlantic-union-bank-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Atlantic Union Bank's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Regional Bank
- Virginia
- Open Finance
---
