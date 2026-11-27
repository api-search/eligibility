---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Money Transfer Service is available to residents of the United States only, unless otherwise specifically agreed to by Remitly.
  entity_types:
  - text: Our Money Transfer Service under this Agreement is only made available to consumers, meaning for use by individuals for personal, family, or household purposes.
    type: individual
  - text: To use our international money transfer services for your business, please open a Business Account as detailed in our Business Account Agreement
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to create a Remitly Account or use the Money Transfer Service as a Sender.
    value: '18'
  restricted_uses:
  - summary: No business use of consumer account
    text: By using our Money Transfer Service under the terms of this Agreement for any other purpose, including for business purposes, you are in breach of this Agreement.
  - summary: Restricted transaction purposes
    text: 'use the Money Transfer Service for any of the following: sexually-oriented materials or services, gambling activities , fraud, money-laundering, the funding of terrorist organizations, or the purchase or sale of tobacco, tobacco related paraphernalia, firearms, prescription drugs, or other controlled substances;'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Pending the successful completion of any necessary steps we are required to take to verify your identity, you will then have access to your own Remitly Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Remitly
provenance_date: '2026-11-10'
provider_name: Remitly
provider_slug: remitly
slug: remitly-eligibility
source_date: '2026-11-10'
source_filename: remitly-eligibility.yml
source_heading: Eligibility
source_page: https://www.remitly.com/us/en/home/agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Remitly\naid: remitly\nurl: https://www.remitly.com/us/en/home/agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Money Transfer Service is available to residents of the United States only, unless otherwise specifically\n    agreed to by Remitly.\nentity_types:\n- type: individual\n  text: Our Money Transfer Service under this Agreement is only made available to consumers, meaning for use by\n    individuals for personal, family, or household purposes.\n- type: business\n  text: To use our international money transfer services for your business,\
  \ please open a Business Account as detailed\n    in our Business Account Agreement\nrestricted_uses:\n- summary: No business use of consumer account\n  text: By using our Money Transfer Service under the terms of this Agreement for any other purpose, including for\n    business purposes, you are in breach of this Agreement.\n- summary: Restricted transaction purposes\n  text: 'use the Money Transfer Service for any of the following: sexually-oriented materials or services, gambling\n    activities , fraud, money-laundering, the funding of terrorist organizations, or the purchase or sale of tobacco,\n    tobacco related paraphernalia, firearms, prescription drugs, or other controlled substances;'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Pending the successful completion of any necessary steps we are required to take to verify your identity,\n    you will then have access to your own Remitly Account\nminimum_age:\n  value: '18'\n  text: You must be at\
  \ least eighteen (18) years old to create a Remitly Account or use the Money Transfer Service\n    as a Sender.\n"
source_yaml_url: https://artifacts.apis.io/remitly/eligibility/remitly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Remitly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Money Transfer
- Remittances
- Cross-Border Payments
- Payments
- Financial Services
---
