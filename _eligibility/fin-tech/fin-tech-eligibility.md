---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services are not offered to persons in Restricted Jurisdictions; the list is not enumerated. Rewards are not available if Customer is resident in the EEA, Singapore, or Japan.
  minimum_age:
    text: CUSTOMER IS OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FIN
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Fin reserves the right, but has no obligation, to request information from Customer to verify Customer's identity in order to comply with laws and regulations governing payments
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fin
provenance_date: '2026-11-09'
provider_name: Fin
provider_slug: fin-tech
slug: fin-tech-eligibility
source_date: '2026-11-09'
source_filename: fin-tech-eligibility.yml
source_heading: Eligibility
source_page: https://www.fin.tech/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fin\naid: fin-tech\nurl: https://www.fin.tech/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Services are not offered to persons in Restricted Jurisdictions; the list is not enumerated. Rewards are\n    not available if Customer is resident in the EEA, Singapore, or Japan.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Fin reserves the right, but has no obligation, to request information from Customer to verify Customer's\n    identity in order to comply with laws and regulations governing payments\nminimum_age:\n\
  \  value: null\n  text: CUSTOMER IS OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FIN\n"
source_yaml_url: https://artifacts.apis.io/fin-tech/eligibility/fin-tech-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from Fin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Payments
- Stablecoins
- Banking
- Cross-Border Payments
- Settlement
- Fintech
---
