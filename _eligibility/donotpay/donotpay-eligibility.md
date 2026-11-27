---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Arbitration Agreement only applies to you if your country of residence or establishment is the United States.
  entity_types:
  - text: The Service is available to anyone who is eighteen (18) years of age and older, has a valid email address, a valid credit card, and has enrolled in the Service at DoNotPay.com.
    type: individual
  minimum_age:
    text: anyone who is eighteen (18) years of age and older
    value: '18'
  restricted_uses:
  - summary: Ban notification
    text: You may not use any part of our website or intellectual property if you have been notified that you are not permitted to do so
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order to allow you to use certain Services, we may be required to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DoNotPay
provenance_date: '2026-11-09'
provider_name: DoNotPay
provider_slug: donotpay
slug: donotpay-eligibility
source_date: '2026-11-09'
source_filename: donotpay-eligibility.yml
source_heading: Eligibility
source_page: https://donotpay.com/learn/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DoNotPay\naid: donotpay\nurl: https://donotpay.com/learn/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Arbitration Agreement only applies to you if your country of residence or establishment is the United\n    States.\nentity_types:\n- type: individual\n  text: The Service is available to anyone who is eighteen (18) years of age and older, has a valid email address,\n    a valid credit card, and has enrolled in the Service at DoNotPay.com.\nrestricted_uses:\n- summary: Ban notification\n  text: You may not use any part of our website or intellectual property\
  \ if you have been notified that you are\n    not permitted to do so\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In order to allow you to use certain Services, we may be required to verify your identity.\nminimum_age:\n  value: '18'\n  text: anyone who is eighteen (18) years of age and older\n"
source_yaml_url: https://artifacts.apis.io/donotpay/eligibility/donotpay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from DoNotPay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Legal Tech
- Consumer Advocacy
- Artificial Intelligence
- Automation
- Consumer Protection
---
