---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Zeller Australia Pty Ltd ACN 649 001 383 (referred to as Zeller , we , us , our ) permits a user
  entity_types:
  - text: only submit a Transaction where you are the supplier of the goods and/or services and not submit transactions on behalf of a third party
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Self-carding and illegitimate transactions
    text: not for a legitimate purpose, for example 'self-carding'
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Zeller is required to verify the identity of its Users as well as certain information about Users' beneficial owners
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zeller
provenance_date: '2026-11-10'
provider_name: Zeller
provider_slug: zeller
slug: zeller-eligibility
source_date: '2026-11-10'
source_filename: zeller-eligibility.yml
source_heading: Eligibility
source_page: https://www.myzeller.com/au/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zeller\naid: zeller\nurl: https://www.myzeller.com/au/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Zeller Australia Pty Ltd ACN 649 001 383 (referred to as Zeller , we , us , our ) permits a user\nentity_types:\n- type: business\n  text: only submit a Transaction where you are the supplier of the goods and/or services and not submit transactions\n    on behalf of a third party\nrestricted_uses:\n- summary: Self-carding and illegitimate transactions\n  text: not for a legitimate purpose, for example 'self-carding'\nverification:\n  kyc: true\n  kyb:\
  \ null\n  approval_required: true\n  text: Zeller is required to verify the identity of its Users as well as certain information about Users' beneficial\n    owners\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zeller/eligibility/zeller-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Zeller's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Australia
- Payment Gateway
- Payment Processing
- Acquiring
- Merchant Services
- Point-of-Sale
- In-Person Payments
- Tap to Pay
- Small Business
---
