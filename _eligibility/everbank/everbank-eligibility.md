---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Any offer for or display of any product, service, content and/or information made in connection with this Site is void where prohibited by applicable law.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use of accounts to breach security
    text: use your account to breach security of another account or attempt to gain unauthorized access to another network or server
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
name: EverBank
provenance_date: '2026-11-09'
provider_name: EverBank
provider_slug: everbank
slug: everbank-eligibility
source_date: '2026-11-09'
source_filename: everbank-eligibility.yml
source_heading: Eligibility
source_page: https://www.everbank.com/legal/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EverBank\naid: everbank\nurl: https://www.everbank.com/legal/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Any offer for or display of any product, service, content and/or information made in connection with this\n    Site is void where prohibited by applicable law.\nentity_types: []\nrestricted_uses:\n- summary: Use of accounts to breach security\n  text: use your account to breach security of another account or attempt to gain unauthorized access to another\n    network or server\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/everbank/eligibility/everbank-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from EverBank's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- National Bank
- Deposits
- Commercial Banking
- Open Finance
---
