---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: The Services provided by Magnet Brains through the Website are available and are appropriate only for use in India.
  minimum_age:
    text: You shall register to become a user of the Website only if You are of the age of 18 or above
    value: '18'
  restricted_uses:
  - summary: No cryptocurrency or NFT activity
    text: You do not, and shall not, engage in any activity related to virtual currency, cryptocurrency and other crypto products (like non-fungible tokens or NFTs)
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Magnet Brains may undertake due diligence measures and seek information required for Know-Your- Customer
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pabbly
provenance_date: '2026-11-10'
provider_name: Pabbly
provider_slug: pabbly
slug: pabbly-eligibility
source_date: '2026-11-10'
source_filename: pabbly-eligibility.yml
source_heading: Eligibility
source_page: https://www.pabbly.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pabbly\naid: pabbly\nurl: https://www.pabbly.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: The Services provided by Magnet Brains through the Website are available and are appropriate only for use\n    in India.\nentity_types: []\nrestricted_uses:\n- summary: No cryptocurrency or NFT activity\n  text: You do not, and shall not, engage in any activity related to virtual currency, cryptocurrency and other\n    crypto products (like non-fungible tokens or NFTs)\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text:\
  \ Magnet Brains may undertake due diligence measures and seek information required for Know-Your- Customer\nminimum_age:\n  value: '18'\n  text: You shall register to become a user of the Website only if You are of the age of 18 or above\n"
source_yaml_url: https://artifacts.apis.io/pabbly/eligibility/pabbly-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Pabbly's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Email Marketing
- Subscription Billing
- Billing
- Payments
- Webhook
- Messaging
- WhatsApp
- Email Verification
- Forms
- No-Code
- Software-as-a-Service
---
