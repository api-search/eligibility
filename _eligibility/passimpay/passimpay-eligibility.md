---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you have the authority to enter into the Terms personally or on behalf of the legal entity for whom you are using the Service.
    type: business
  minimum_age:
    text: you are of legal age;
    value: null
  restricted_uses:
  - summary: Sanctioned parties excluded
    text: You also represent that you are (i) not subject to sanctions or otherwise designated on any list of prohibited or restricted parties
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You may be asked to submit additional information and/or documents to enable us to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PassimPay
provenance_date: '2026-11-10'
provider_name: PassimPay
provider_slug: passimpay
slug: passimpay-eligibility
source_date: '2026-11-10'
source_filename: passimpay-eligibility.yml
source_heading: Eligibility
source_page: https://passimpay.io/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PassimPay\naid: passimpay\nurl: https://passimpay.io/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you have the authority to enter into the Terms personally or on behalf of the legal entity for whom you\n    are using the Service.\nrestricted_uses:\n- summary: Sanctioned parties excluded\n  text: You also represent that you are (i) not subject to sanctions or otherwise designated on any list of prohibited\n    or restricted parties\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You may be asked\
  \ to submit additional information and/or documents to enable us to verify your identity.\nminimum_age:\n  value: null\n  text: you are of legal age;\n"
source_yaml_url: https://artifacts.apis.io/passimpay/eligibility/passimpay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from PassimPay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Cryptocurrency
- B2B
- Gateways
---
