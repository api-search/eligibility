---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years or older to sign up for an account and use our Services.
    type: individual
  - text: if you have accepted these Terms on behalf of any person or entity, you represent that you have legal authority to do so
    type: business
  minimum_age:
    text: You must be 18 years or older to sign up for an account and use our Services.
    value: '18'
  restricted_uses:
  - summary: Raffle and sweepstakes compliance
    text: ADMINISTRATORS RECEIVING CONTRIBUTIONS FROM RAFFLE AND SWEEPSTAKES CAMPAIGNS ON THE RALLYUP PLATFORM ARE SOLELY RESPONSIBLE FOR COMPLYING WITH ALL LEGAL, REGULATORY AND TAXING REQUIREMENTS
  - summary: No selling via donation pages
    text: You may not use donation pages within the Services to sell any products, or other items (e.g. raffle tickets, sweepstakes, non-donation payments, other sales) other than the donation payments.
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
name: Rally Up
provenance_date: '2026-11-10'
provider_name: Rally Up
provider_slug: rallyup
slug: rallyup-eligibility
source_date: '2026-11-10'
source_filename: rallyup-eligibility.yml
source_heading: Eligibility
source_page: https://rallyup.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rally Up\naid: rallyup\nurl: https://rallyup.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years or older to sign up for an account and use our Services.\n- type: business\n  text: if you have accepted these Terms on behalf of any person or entity, you represent that you have legal authority\n    to do so\nrestricted_uses:\n- summary: Raffle and sweepstakes compliance\n  text: ADMINISTRATORS RECEIVING CONTRIBUTIONS FROM RAFFLE AND SWEEPSTAKES CAMPAIGNS ON THE RALLYUP PLATFORM ARE\n    SOLELY RESPONSIBLE\
  \ FOR COMPLYING WITH ALL LEGAL, REGULATORY AND TAXING REQUIREMENTS\n- summary: No selling via donation pages\n  text: You may not use donation pages within the Services to sell any products, or other items (e.g. raffle tickets,\n    sweepstakes, non-donation payments, other sales) other than the donation payments.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to sign up for an account and use our Services.\n"
source_yaml_url: https://artifacts.apis.io/rallyup/eligibility/rallyup-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Rally Up's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fundraising
- Non-Profit
- Software-as-a-Service
- Digital Platform
---
