---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Transactions must be settled with a Payment Instrument issued by a U.S. financial institution.
  entity_types:
  - text: If you are under eighteen (18) years of age, you may not use the Service.
    type: individual
  - text: No Transactions on behalf of third parties are permitted.
    type: business
  minimum_age:
    text: If you are under eighteen (18) years of age, you may not use the Service.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: The Service may not be used for commercial purposes.
  - summary: No transfers for third parties
    text: You may not use the Service to transfer funds on behalf of any other natural person or entity.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: LemFi has a regulatory obligation to verify customer information, and to monitor and track certain types of Transaction activity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LemFi
provenance_date: '2026-11-09'
provider_name: LemFi
provider_slug: lemfi
slug: lemfi-eligibility
source_date: '2026-11-09'
source_filename: lemfi-eligibility.yml
source_heading: Eligibility
source_page: https://lemfi.com/en-us/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LemFi\naid: lemfi\nurl: https://lemfi.com/en-us/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Transactions must be settled with a Payment Instrument issued by a U.S. financial institution.\nentity_types:\n- type: individual\n  text: If you are under eighteen (18) years of age, you may not use the Service.\n- type: business\n  text: No Transactions on behalf of third parties are permitted.\nrestricted_uses:\n- summary: No commercial use\n  text: The Service may not be used for commercial purposes.\n- summary: No transfers for third parties\n  text: You may not use the\
  \ Service to transfer funds on behalf of any other natural person or entity.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: LemFi has a regulatory obligation to verify customer information, and to monitor and track certain types\n    of Transaction activity.\nminimum_age:\n  value: '18'\n  text: If you are under eighteen (18) years of age, you may not use the Service.\n"
source_yaml_url: https://artifacts.apis.io/lemfi/eligibility/lemfi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from LemFi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Payments
- Remittances
- Cross-Border Payments
- Money Transfer
- Consumer Finance
- Mobile Banking
- eSIM
---
