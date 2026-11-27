---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Scraping and automated gathering
    text: You must not use any robot, spider, site search/retrieval application or other manual or automatic device to retrieve, index, “scrape,” “data mine” or in any way gather Website content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Certain services made available on the Website may require prior registration to permit their use.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Trust Payments
provenance_date: '2026-11-10'
provider_name: Trust Payments
provider_slug: trust-payments
slug: trust-payments-eligibility
source_date: '2026-11-10'
source_filename: trust-payments-eligibility.yml
source_heading: Eligibility
source_page: https://www.trustpayments.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trust Payments\naid: trust-payments\nurl: https://www.trustpayments.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Scraping and automated gathering\n  text: You must not use any robot, spider, site search/retrieval application or other manual or automatic device\n    to retrieve, index, “scrape,” “data mine” or in any way gather Website content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Certain services made available on the Website may require prior registration to permit their\
  \ use.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trust-payments/eligibility/trust-payments-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Trust Payments's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- Tokenization
- Subscription
- 3D Secure
- Point-of-Sale
- Webhook
- Payouts
---
