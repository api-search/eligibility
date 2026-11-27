---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: The Platform is controlled and offered by the Company from its facilities in India. If You are a user outside India, please take note the Company is subject only to Indian law and only to the jurisdiction of Indian courts.
  entity_types:
  - text: Your use of the Platform and specifically, Your acceptance of these Terms as aforesaid shall be deemed to be a representation from You that You are above 18 years of age, or possess legal parental or guardian consent
    type: individual
  minimum_age:
    text: You are above 18 years of age, or possess legal parental or guardian consent
    value: '18'
  restricted_uses:
  - summary: Fraud, money laundering or unlawful use
    text: You shall not use the Platform or the Services provided by the Company for committing fraud, embezzlement, money laundering or for any other unlawful and/or illegal purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: The Company, via the Platform, facilitates completion of the loan application form, collection of KYC documents and acceptance of the loan agreement provided by the Lender(s)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Money View
provenance_date: '2026-11-10'
provider_name: Money View
provider_slug: money-view
slug: money-view-eligibility
source_date: '2026-11-10'
source_filename: money-view-eligibility.yml
source_heading: Eligibility
source_page: https://moneyview.in:443/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Money View\naid: money-view\nurl: https://moneyview.in:443/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: The Platform is controlled and offered by the Company from its facilities in India. If You are a user outside\n    India, please take note the Company is subject only to Indian law and only to the jurisdiction of Indian courts.\nentity_types:\n- type: individual\n  text: Your use of the Platform and specifically, Your acceptance of these Terms as aforesaid shall be deemed to\n    be a representation from You that You are above 18 years of age, or possess\
  \ legal parental or guardian consent\nrestricted_uses:\n- summary: Fraud, money laundering or unlawful use\n  text: You shall not use the Platform or the Services provided by the Company for committing fraud, embezzlement,\n    money laundering or for any other unlawful and/or illegal purposes.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: The Company, via the Platform, facilitates completion of the loan application form, collection of KYC documents\n    and acceptance of the loan agreement provided by the Lender(s)\nminimum_age:\n  value: '18'\n  text: You are above 18 years of age, or possess legal parental or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/money-view/eligibility/money-view-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Money View's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Fintech
- Lending
- Personal Loans
- Credit
- Payments
- Insurance
- India
---
