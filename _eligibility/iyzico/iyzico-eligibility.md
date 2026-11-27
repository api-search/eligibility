---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This “Business” Framework Service Agreement General Terms
    type: business
  - text: “Kendim İçin” Çerçeve Hizmet Sözleşmesi Genel Şartları
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal gambling and betting
    text: Illegal gambling and betting
  - summary: Pyramid sales systems
    text: Establishing a pyramid sales system and any suspicion of the establishment of a pyramid sales system
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: provided that identity verification procedures are successfully completed, and the Agreement is concluded with iyzico
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Iyzico
provenance_date: '2026-11-09'
provider_name: Iyzico
provider_slug: iyzico
slug: iyzico-eligibility
source_date: '2026-11-09'
source_filename: iyzico-eligibility.yml
source_heading: Eligibility
source_page: https://www.iyzico.com/en/general-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Iyzico\naid: iyzico\nurl: https://www.iyzico.com/en/general-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This “Business” Framework Service Agreement General Terms\n- type: individual\n  text: “Kendim İçin” Çerçeve Hizmet Sözleşmesi Genel Şartları\nrestricted_uses:\n- summary: Illegal gambling and betting\n  text: Illegal gambling and betting\n- summary: Pyramid sales systems\n  text: Establishing a pyramid sales system and any suspicion of the establishment of a pyramid sales system\nverification:\n  kyc: true\n  kyb: null\n\
  \  approval_required: true\n  text: provided that identity verification procedures are successfully completed, and the Agreement is concluded\n    with iyzico\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/iyzico/eligibility/iyzico-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Iyzico's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Payment Gateway
- Card Payments
- Checkout
- Subscription
- Marketplace
- Turkey
- 3D Secure
---
