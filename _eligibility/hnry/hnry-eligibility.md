---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Where a Client is an individual, for additional self-employed income that is received directly by the Client and not processed via a Hnry Account after the effective date of this Agreement, the Client agrees to pay the Supplier 1% +GST of that income.
    type: individual
  - text: The Client agrees and represents that it is acquiring the Services for the purposes of a business and that the New Zealand Consumer Guarantees Act 1993 does not apply to the supply of the Services or the Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited income types
    text: The Client must not use the Hnry Account, or any Hnry invoicing or payment service, to receive or process income derived from gambling, crypto-asset activities, “Quasi Cash” transactions, or any illegal goods or services.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: By agreeing to Hnry’s terms, the Client consents to their information being passed to, and checked with, the document issuer, official record holder, a credit bureau and authorised third parties for the purpose of verifying the Client’s identity and address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hnry
provenance_date: '2026-11-09'
provider_name: Hnry
provider_slug: hnry
slug: hnry-eligibility
source_date: '2026-11-09'
source_filename: hnry-eligibility.yml
source_heading: Eligibility
source_page: https://hnry.co.nz/agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hnry\naid: hnry\nurl: https://hnry.co.nz/agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Where a Client is an individual, for additional self-employed income that is received directly by the Client\n    and not processed via a Hnry Account after the effective date of this Agreement, the Client agrees to pay the\n    Supplier 1% +GST of that income.\n- type: business\n  text: The Client agrees and represents that it is acquiring the Services for the purposes of a business and that\n    the New Zealand Consumer\
  \ Guarantees Act 1993 does not apply to the supply of the Services or the Agreement.\nrestricted_uses:\n- summary: Prohibited income types\n  text: The Client must not use the Hnry Account, or any Hnry invoicing or payment service, to receive or process\n    income derived from gambling, crypto-asset activities, “Quasi Cash” transactions, or any illegal goods or services.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: By agreeing to Hnry’s terms, the Client consents to their information being passed to, and checked with,\n    the document issuer, official record holder, a credit bureau and authorised third parties for the purpose of\n    verifying the Client’s identity and address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hnry/eligibility/hnry-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Hnry's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Tax
- Payments
- Invoicing
- Expense Management
- Financial Services
- Sole Traders
- Payroll
- Fintech
- New Zealand
- Australia
- United Kingdom
---
