---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU AS THE COMPANY OR THE LEGAL ENTITY THAT WILL BE UTILIZING THE SAAS PLATFORM
    type: business
  - text: If Client is an agency or contractor of the United States Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export to prohibited persons
    text: 'Client shall not export, re-export, access or grant access to the SaaS Platform and all related technology, information, materials and any upgrades thereto to: (a) any Prohibited Persons'
  - summary: No sensitive regulated data unless agreed
    text: except as otherwise agreed by the parties, store in or process any personal health information or data, credit card data, personal financial data, or other such sensitive regulated data not required by the Documentation
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
name: ClassWallet
provenance_date: '2026-11-09'
provider_name: ClassWallet
provider_slug: classwallet
slug: classwallet-eligibility
source_date: '2026-11-09'
source_filename: classwallet-eligibility.yml
source_heading: Eligibility
source_page: https://classwallet.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClassWallet\naid: classwallet\nurl: https://classwallet.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: YOU AS THE COMPANY OR THE LEGAL ENTITY THAT WILL BE UTILIZING THE SAAS PLATFORM\n- type: government\n  text: If Client is an agency or contractor of the United States Government\nrestricted_uses:\n- summary: Export to prohibited persons\n  text: 'Client shall not export, re-export, access or grant access to the SaaS Platform and all related technology,\n    information, materials and any upgrades thereto to: (a) any\
  \ Prohibited Persons'\n- summary: No sensitive regulated data unless agreed\n  text: except as otherwise agreed by the parties, store in or process any personal health information or data,\n    credit card data, personal financial data, or other such sensitive regulated data not required by the Documentation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/classwallet/eligibility/classwallet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from ClassWallet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Digital Wallet
- Fund Management
- Education
- EdTech
- Government
- Compliance
---
