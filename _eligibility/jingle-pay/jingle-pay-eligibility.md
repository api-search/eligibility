---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: Our Mobile Application is intended for use by people resident in the UAE.
  entity_types:
  - text: In case the customer is a corporate, we will deal with the person(s) duly authorized by the company supported by an authorization letter signed by the authorized signatory of the company.
    type: business
  minimum_age:
    text: you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No adult or gambling purchases with Card
    text: You also agree not to use the Card for accessing or purchasing goods from adult or gambling locations or internet sites, or for any other unlawful activity.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: The activation of the service is subject to successful verification of your identity by us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jingle Pay
provenance_date: '2026-11-09'
provider_name: Jingle Pay
provider_slug: jingle-pay
slug: jingle-pay-eligibility
source_date: '2026-11-09'
source_filename: jingle-pay-eligibility.yml
source_heading: Eligibility
source_page: https://jinglepay.com/are/en/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jingle Pay\naid: jingle-pay\nurl: https://jinglepay.com/are/en/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: Our Mobile Application is intended for use by people resident in the UAE.\nentity_types:\n- type: business\n  text: In case the customer is a corporate, we will deal with the person(s) duly authorized by the company supported\n    by an authorization letter signed by the authorized signatory of the company.\nrestricted_uses:\n- summary: No adult or gambling purchases with Card\n  text: You also agree not to use the Card for accessing\
  \ or purchasing goods from adult or gambling locations or\n    internet sites, or for any other unlawful activity.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: The activation of the service is subject to successful verification of your identity by us.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/jingle-pay/eligibility/jingle-pay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Jingle Pay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Remittances
- Money Transfer
- Digital Wallet
- Financial Services
- MENA
---
