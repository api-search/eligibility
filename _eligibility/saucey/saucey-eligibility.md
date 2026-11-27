---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be permitted to agree to these Terms under the laws of your place of residence including having sufficient legal capacity.
    type: individual
  minimum_age:
    text: By completing an order for products with a legal minimum age for purchase through the use of the Services, you agree that you are 21 years of age or older
    value: '21'
  restricted_uses:
  - summary: Alcohol purchases for self or adult gifting only
    text: YOU ARE PURCHASING SOLELY FOR (i) SELF CONSUMPTION OR (ii) GIFTING TO A PERSON IN THE U.S. WHO IS AT LEAST 21 YEARS OLD.
  - summary: Non-commercial personal use only
    text: solely for your lawful, personal, non-commercial use
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: you consent to Saucey and its Sellers verifying your age and identity through third-party verification services and by requiring valid government-issued identification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Saucey
provenance_date: '2026-11-10'
provider_name: Saucey
provider_slug: saucey
slug: saucey-eligibility
source_date: '2026-11-10'
source_filename: saucey-eligibility.yml
source_heading: Eligibility
source_page: https://saucey.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Saucey\naid: saucey\nurl: https://saucey.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be permitted to agree to these Terms under the laws of your place of residence including having\n    sufficient legal capacity.\nrestricted_uses:\n- summary: Alcohol purchases for self or adult gifting only\n  text: YOU ARE PURCHASING SOLELY FOR (i) SELF CONSUMPTION OR (ii) GIFTING TO A PERSON IN THE U.S. WHO IS AT LEAST\n    21 YEARS OLD.\n- summary: Non-commercial personal use only\n  text: solely for your lawful,\
  \ personal, non-commercial use\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: you consent to Saucey and its Sellers verifying your age and identity through third-party verification services\n    and by requiring valid government-issued identification.\nminimum_age:\n  value: '21'\n  text: By completing an order for products with a legal minimum age for purchase through the use of the Services,\n    you agree that you are 21 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/saucey/eligibility/saucey-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Saucey's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Alcohol Delivery
- On-Demand Delivery
- E-Commerce
- Logistics
- Consumer
- Marketplace
- Alcohol
- Delivery
- On-Demand
---
