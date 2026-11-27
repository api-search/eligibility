---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This Website is only suitable for individuals aged 13 years and older.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: MirrorFly reserves the right to impose limitations on account access, such as login frequency, session timeouts, and account verification requirements
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MirrorFly Messages API
provenance_date: '2026-11-10'
provider_name: MirrorFly Messages API
provider_slug: mirrorfly-messages-api
slug: mirrorfly-messages-api-eligibility
source_date: '2026-11-10'
source_filename: mirrorfly-messages-api-eligibility.yml
source_heading: Eligibility
source_page: https://www.mirrorfly.com/terms-and-conditions.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MirrorFly Messages API\naid: mirrorfly-messages-api\nurl: https://www.mirrorfly.com/terms-and-conditions.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: MirrorFly reserves the right to impose limitations on account access, such as login frequency, session timeouts,\n    and account verification requirements\nminimum_age:\n  value: '13'\n  text: This Website is only suitable for individuals aged 13 years and older.\n"
source_yaml_url: https://artifacts.apis.io/mirrorfly-messages-api/eligibility/mirrorfly-messages-api-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from MirrorFly Messages API's own page on 2026-11-10.
synthetic: false
tags:
- CPaaS
- Communications
- Chat / Messaging API
- Voice API
- Video API
- SIP/VoIP
- Real-Time Communication
- SDK
- Self-hosted / On-premise
- AI Agents / Chatbots
- Contact Center
---
