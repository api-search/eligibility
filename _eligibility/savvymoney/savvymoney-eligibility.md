---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Programs is not authorized in any jurisdiction that does not give effect to all provisions of this TOS
  entity_types:
  - text: Your right to access and use the Programs is personal to You and is not transferable by You to any other person or entity.
    type: individual
  minimum_age:
    text: We do not obtain the credit report or credit information of any user who is less than eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may access and use the Programs for only lawful purposes.
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
name: SavvyMoney
provenance_date: '2026-11-10'
provider_name: SavvyMoney
provider_slug: savvymoney
slug: savvymoney-eligibility
source_date: '2026-11-10'
source_filename: savvymoney-eligibility.yml
source_heading: Eligibility
source_page: https://www.savvymoney.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SavvyMoney\naid: savvymoney\nurl: https://www.savvymoney.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Programs is not authorized in any jurisdiction that does not give effect to all provisions of\n    this TOS\nentity_types:\n- type: individual\n  text: Your right to access and use the Programs is personal to You and is not transferable by You to any other\n    person or entity.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may access and use the Programs for only lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: We do not obtain the credit report or credit information of any user who is less than eighteen (18) years\n    of age.\n"
source_yaml_url: https://artifacts.apis.io/savvymoney/eligibility/savvymoney-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SavvyMoney's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Credit Score
- Credit Monitoring
- Financial Wellness
- Banking
- Credit Union
- Fintech
- SSO
- Embedded Finance
- Lending
- Account Opening
---
