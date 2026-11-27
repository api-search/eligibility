---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Enterprise Customer” means an entity that purchases the Services for its own use.
    type: business
  - text: “Channel Partner" means an entity such as reseller or aggregator that purchases and commercializes the Services to its customers
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: to distribute any Trojan horse, worm, malicious or destructive code or any instructions activating such code, or virus;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Singtel Mobile reserves the right not to accept or proceed with any application for the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Singtel
provenance_date: '2026-11-10'
provider_name: Singtel
provider_slug: singtel
slug: singtel-eligibility
source_date: '2026-11-10'
source_filename: singtel-eligibility.yml
source_heading: Eligibility
source_page: https://www.singtel.com/business/products-services/mobility/terms/singverify-tnc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Singtel\naid: singtel\nurl: https://www.singtel.com/business/products-services/mobility/terms/singverify-tnc\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Enterprise Customer” means an entity that purchases the Services for its own use.\n- type: business\n  text: “Channel Partner\" means an entity such as reseller or aggregator that purchases and commercializes the Services\n    to its customers\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: to distribute any Trojan horse, worm, malicious or destructive code or any\
  \ instructions activating such\n    code, or virus;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Singtel Mobile reserves the right not to accept or proceed with any application for the Services\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/singtel/eligibility/singtel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Singtel's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- Singapore
- Mobile Network Operator
- Network APIs
- CAMARA
- Open Gateway
- SIM Swap
- Identity Verification
- Fraud Prevention
- CPaaS
- Messaging
- Voice
- IoT
- 5G
- Edge Computing
- Aduna
---
