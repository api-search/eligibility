---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: EFEX only facilitates International Transfers to certain countries. All Linked Bank Accounts must be with financial institutions in the United States.
  entity_types:
  - text: The Services are available exclusively to business entities and commercial users acting for business or commercial purposes.
    type: business
  - text: EFEX does not provide services to individuals acting for personal, family, or household purposes.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unsupported businesses and transactions
    text: We do not support businesses or transactions which are involved in any of the categories below, such businesses or transactions may be declined.
  - summary: Restricted activities
    text: 'You may not use our Services: in any way that breaches any applicable local, national, or international law or regulation'
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
name: EFEX (Ventu)
provenance_date: '2026-11-09'
provider_name: EFEX (Ventu)
provider_slug: efex-ventu
slug: efex-ventu-eligibility
source_date: '2026-11-09'
source_filename: efex-ventu-eligibility.yml
source_heading: Eligibility
source_page: https://legal.efex.com/TermsOfService
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EFEX (Ventu)\naid: efex-ventu\nurl: https://legal.efex.com/TermsOfService\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: EFEX only facilitates International Transfers to certain countries. All Linked Bank Accounts must be with\n    financial institutions in the United States.\nentity_types:\n- type: business\n  text: The Services are available exclusively to business entities and commercial users acting for business or\n    commercial purposes.\n- type: individual\n  text: EFEX does not provide services to individuals acting for personal, family, or household\
  \ purposes.\nrestricted_uses:\n- summary: Unsupported businesses and transactions\n  text: We do not support businesses or transactions which are involved in any of the categories below, such businesses\n    or transactions may be declined.\n- summary: Restricted activities\n  text: 'You may not use our Services: in any way that breaches any applicable local, national, or international\n    law or regulation'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/efex-ventu/eligibility/efex-ventu-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from EFEX (Ventu)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Cross-Border Payments
- Foreign Exchange
- Fintech
- Money Transfer
- Treasury
- Multi-Currency
- Mexico
---
