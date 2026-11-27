---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Content is solely directed to individuals residing in the United States.
  entity_types:
  - text: The Content is solely directed to individuals residing in the United States.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal gambling, firearms, controlled substances, obscenity
    text: any form of illegal gambling activities (including underage gambling); firearms, controlled substances, prescription drugs, steroids, or related paraphernalia; obscenity
  - summary: Minors
    text: The Network may not be used to make payments by persons under thirteen years old
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We use third party vendors to assist in verifying your payment information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PayNearMe
provenance_date: '2026-11-10'
provider_name: PayNearMe
provider_slug: paynearme
slug: paynearme-eligibility
source_date: '2026-11-10'
source_filename: paynearme-eligibility.yml
source_heading: Eligibility
source_page: https://www.paynearme.com/doc/bn_user/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayNearMe\naid: paynearme\nurl: https://www.paynearme.com/doc/bn_user/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Content is solely directed to individuals residing in the United States.\nentity_types:\n- type: individual\n  text: The Content is solely directed to individuals residing in the United States.\nrestricted_uses:\n- summary: Illegal gambling, firearms, controlled substances, obscenity\n  text: any form of illegal gambling activities (including underage gambling); firearms, controlled substances,\n    prescription drugs, steroids, or related paraphernalia;\
  \ obscenity\n- summary: Minors\n  text: The Network may not be used to make payments by persons under thirteen years old\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: We use third party vendors to assist in verifying your payment information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paynearme/eligibility/paynearme-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from PayNearMe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Billing
- ACH
- Cash
- Digital Wallet
- Lending
- iGaming
- Webhook
---
