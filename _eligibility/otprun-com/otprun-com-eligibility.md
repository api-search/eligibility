---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use OTP Run on behalf of a company, you confirm that you may accept these terms for it, and “you” means that company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spam and unlawful messaging
    text: send spam, unsolicited bulk messages, or messages to bought or scraped lists of numbers
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
name: otprun-com
provenance_date: '2026-11-10'
provider_name: otprun-com
provider_slug: otprun-com
slug: otprun-com-eligibility
source_date: '2026-11-10'
source_filename: otprun-com-eligibility.yml
source_heading: Eligibility
source_page: https://otprun.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: otprun-com\naid: otprun-com\nurl: https://otprun.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use OTP Run on behalf of a company, you confirm that you may accept these terms for it, and “you”\n    means that company.\nrestricted_uses:\n- summary: Spam and unlawful messaging\n  text: send spam, unsolicited bulk messages, or messages to bought or scraped lists of numbers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/otprun-com/eligibility/otprun-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from otprun-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Messaging
- WhatsApp
- Artificial Intelligence
- Software-as-a-Service
---
