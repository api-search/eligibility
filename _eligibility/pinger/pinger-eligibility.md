---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - GB
    - EU
    served:
    - US
    - CA
    text: APPS ARE ONLY MADE AVAILABLE FOR DOWNLOAD FROM U.S. AND CANADIAN APP STORES ... IF YOU ARE A RESIDENT OF THE UNITED KINGDOM OR THE EU ... THEN NO LICENSE RIGHTS ARE GRANTED
  entity_types:
  - text: Accounts are for your personal use and may not be transferred or assigned by you to a third party.
    type: individual
  minimum_age:
    text: Apps, Services and Pinger websites are not intended for children under the age of 16, so children under the age of 16 should not use them at any time. If you are under 18, you represent that your legal guardian has reviewed and agreed to these terms.
    value: '16'
  restricted_uses:
  - summary: High-risk financial and other spam categories
    text: engage in high-risk financial services (such as payday loans; short term high-interest loans; auto, mortgage or student loans; debt collection, gambling/sweepstakes; stock alerts; or cryptocurrency)
  - summary: Use in violation of law (e.g. texting while driving)
    text: You agree that you will not use the Apps or Services in violation of applicable law (e.g. no texting while driving)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- GB
- EU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pinger
provenance_date: '2026-11-10'
provider_name: Pinger
provider_slug: pinger
slug: pinger-eligibility
source_date: '2026-11-10'
source_filename: pinger-eligibility.yml
source_heading: Eligibility
source_page: https://www.pinger.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pinger\naid: pinger\nurl: https://www.pinger.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded:\n  - GB\n  - EU\n  text: APPS ARE ONLY MADE AVAILABLE FOR DOWNLOAD FROM U.S. AND CANADIAN APP STORES ... IF YOU ARE A RESIDENT OF\n    THE UNITED KINGDOM OR THE EU ... THEN NO LICENSE RIGHTS ARE GRANTED\nentity_types:\n- type: individual\n  text: Accounts are for your personal use and may not be transferred or assigned by you to a third party.\nrestricted_uses:\n- summary: High-risk financial and other spam categories\n  text: engage in high-risk\
  \ financial services (such as payday loans; short term high-interest loans; auto, mortgage\n    or student loans; debt collection, gambling/sweepstakes; stock alerts; or cryptocurrency)\n- summary: Use in violation of law (e.g. texting while driving)\n  text: You agree that you will not use the Apps or Services in violation of applicable law (e.g. no texting while\n    driving)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Apps, Services and Pinger websites are not intended for children under the age of 16, so children under\n    the age of 16 should not use them at any time. If you are under 18, you represent that your legal guardian has\n    reviewed and agreed to these terms.\n"
source_yaml_url: https://artifacts.apis.io/pinger/eligibility/pinger-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pinger's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Telecommunications
- Messaging
- SMS
- Voice
- Mobile App
- Phone Numbers
- Consumer Applications
- Small Business
---
