---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Site is only for users in which we are able to offer and/or provide our services.
  entity_types:
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our Site'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Domestic and private use only for consumers
    text: Please note that we only provide our Site for domestic and private use. You agree not to use our Site for any commercial or business purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Shieldpay
provenance_date: '2026-11-10'
provider_name: Shieldpay
provider_slug: shieldpay
slug: shieldpay-eligibility
source_date: '2026-11-10'
source_filename: shieldpay-eligibility.yml
source_heading: Eligibility
source_page: https://www.shieldpay.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shieldpay\naid: shieldpay\nurl: https://www.shieldpay.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our Site is only for users in which we are able to offer and/or provide our services.\nentity_types:\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n    that may apply to our Site'\nrestricted_uses:\n- summary: Domestic and private use only for consumers\n  text: Please note that we only provide our Site for domestic and private use. You agree not to use our Site for\n  \
  \  any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shieldpay/eligibility/shieldpay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Shieldpay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Escrow
- Legal Tech
- Fintech
- Compliance
- KYC
- Banking
---
