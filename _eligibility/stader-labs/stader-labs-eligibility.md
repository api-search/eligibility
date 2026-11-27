---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACCEPTING THESE TERMS AND THE NOTICE ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE LEGAL AUTHORITY TO ACCEPT THESE TERMS
    type: business
  minimum_age:
    text: To access the App, you must be at least eighteen (18) years old or of legal age to enter into an agreement as determined by the laws of the country/ territory where you live.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons or jurisdictions
    text: (ii) located, organised, citizen or resident in a country or territory that is, or whose government is, the subject of Sanctions
  - summary: Illegal activity and money laundering
    text: you will not use the Smart Contracts, the Site or the App to finance, engage in, or otherwise support any unlawful activities
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Upon our request, you shall immediately provide us with information and documents that we, in our sole discretion, deem necessary or appropriate to conduct "Know Your Customer" and "Anti-Money Laundering" checks.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Stader Labs
provenance_date: '2026-11-10'
provider_name: Stader Labs
provider_slug: stader-labs
slug: stader-labs-eligibility
source_date: '2026-11-10'
source_filename: stader-labs-eligibility.yml
source_heading: Eligibility
source_page: https://www.staderlabs.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stader Labs\naid: stader-labs\nurl: https://www.staderlabs.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACCEPTING THESE TERMS AND THE NOTICE ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT\n    THAT YOU HAVE THE LEGAL AUTHORITY TO ACCEPT THESE TERMS\nrestricted_uses:\n- summary: Sanctioned persons or jurisdictions\n  text: (ii) located, organised, citizen or resident in a country or territory that is, or whose government is,\n    the subject of Sanctions\n- summary: Illegal activity and\
  \ money laundering\n  text: you will not use the Smart Contracts, the Site or the App to finance, engage in, or otherwise support any\n    unlawful activities\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Upon our request, you shall immediately provide us with information and documents that we, in our sole discretion,\n    deem necessary or appropriate to conduct \"Know Your Customer\" and \"Anti-Money Laundering\" checks.\nminimum_age:\n  value: '18'\n  text: To access the App, you must be at least eighteen (18) years old or of legal age to enter into an agreement\n    as determined by the laws of the country/ territory where you live.\n"
source_yaml_url: https://artifacts.apis.io/stader-labs/eligibility/stader-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Stader Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- DeFi
- Liquid Staking
- Blockchain
- Staking
- Web3
- Ethereum
---
