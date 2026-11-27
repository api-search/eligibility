---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU REPRESENT AND WARRANT THAT YOU ARE AUTHORIZED TO BIND CUSTOMER
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal activity
    text: Customer is engaging in illegal activities in connection with its use of the Service
  - summary: Third-party rights and laws
    text: Customer represents and warrants that the Customer Product(s) (and the development, use, distribution and marketing thereof) will (i) comply with all laws and regulations and (ii) not violate any of the rights of any third party
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
name: BlockCypher
provenance_date: '2026-11-09'
provider_name: BlockCypher
provider_slug: blockcypher
slug: blockcypher-eligibility
source_date: '2026-11-09'
source_filename: blockcypher-eligibility.yml
source_heading: Eligibility
source_page: https://www.blockcypher.com/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlockCypher\naid: blockcypher\nurl: https://www.blockcypher.com/terms-of-service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: YOU REPRESENT AND WARRANT THAT YOU ARE AUTHORIZED TO BIND CUSTOMER\nrestricted_uses:\n- summary: Illegal activity\n  text: Customer is engaging in illegal activities in connection with its use of the Service\n- summary: Third-party rights and laws\n  text: Customer represents and warrants that the Customer Product(s) (and the development, use, distribution and\n    marketing thereof) will (i) comply with\
  \ all laws and regulations and (ii) not violate any of the rights of any\n    third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blockcypher/eligibility/blockcypher-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from BlockCypher's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Infrastructure
- Enterprise
---
