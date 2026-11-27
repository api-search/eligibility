---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a company incorporated in [Place], having its registered office at [Address]
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited transactions
    text: The Merchant shall not provide Payment Services in connection with any Transaction that is prohibited under this Agreement, including but not limited to payments related to Prohibited Goods and Services as listed in Schedule 8
  - summary: No Restricted Persons
    text: The Merchant undertakes that the Merchant is not, and will procure that none of Personnel or persons acting on behalf of the foregoing is, a Restricted Person
  verification:
    approval_required: true
    kyb: true
    kyc: null
    text: The Merchant will comply promptly with all requests for information made by QFPay for the purpose of meeting QFPay’s operational and legal requirements to carry out Merchant Due Diligence in relation to the Merchant (including providing personal information about the Merchant’s directors and beneficial owners).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: QFPay
provenance_date: '2026-11-10'
provider_name: QFPay
provider_slug: qfpay
slug: qfpay-eligibility
source_date: '2026-11-10'
source_filename: qfpay-eligibility.yml
source_heading: Eligibility
source_page: https://qfpay.global/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QFPay\naid: qfpay\nurl: https://qfpay.global/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: a company incorporated in [Place], having its registered office at [Address]\nrestricted_uses:\n- summary: Prohibited transactions\n  text: The Merchant shall not provide Payment Services in connection with any Transaction that is prohibited under\n    this Agreement, including but not limited to payments related to Prohibited Goods and Services as listed in\n    Schedule 8\n- summary: No Restricted Persons\n\
  \  text: The Merchant undertakes that the Merchant is not, and will procure that none of Personnel or persons acting\n    on behalf of the foregoing is, a Restricted Person\nverification:\n  kyc: null\n  kyb: true\n  approval_required: true\n  text: The Merchant will comply promptly with all requests for information made by QFPay for the purpose of meeting\n    QFPay’s operational and legal requirements to carry out Merchant Due Diligence in relation to the Merchant (including\n    providing personal information about the Merchant’s directors and beneficial owners).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/qfpay/eligibility/qfpay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from QFPay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
---
