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
  restricted_uses:
  - summary: Illegal or prohibited use of services
    text: Use of MirrorFly’s services for illegal, unethical, or prohibited activities.
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
name: Custom Chat API | MirrorFly
provenance_date: '2026-11-09'
provider_name: Custom Chat API | MirrorFly
provider_slug: custom-chat-api-mirrorfly
slug: custom-chat-api-mirrorfly-eligibility
source_date: '2026-11-09'
source_filename: custom-chat-api-mirrorfly-eligibility.yml
source_heading: Eligibility
source_page: https://www.mirrorfly.com/terms-and-conditions.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Custom Chat API | MirrorFly\naid: custom-chat-api-mirrorfly\nurl: https://www.mirrorfly.com/terms-and-conditions.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or prohibited use of services\n  text: Use of MirrorFly’s services for illegal, unethical, or prohibited activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Website is only suitable for individuals aged 13 years and older.\n"
source_yaml_url: https://artifacts.apis.io/custom-chat-api-mirrorfly/eligibility/custom-chat-api-mirrorfly-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Custom Chat API | MirrorFly's own page on 2026-11-09.
synthetic: false
tags:
- Chat API
- Messaging
- CPaaS
- VoIP
- Voice
- Video Calling
- Contact Center
- Conversational AI
- Chatbots
- Live Streaming
---
