---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of a business, you confirm that you are authorised to bind that business, and “you” refers to that business.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful business purposes only
    text: use the Service only for lawful business purposes
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
name: CodaPhone
provenance_date: '2026-11-09'
provider_name: CodaPhone
provider_slug: codaphone-app
slug: codaphone-app-eligibility
source_date: '2026-11-09'
source_filename: codaphone-app-eligibility.yml
source_heading: Eligibility
source_page: https://codaphone.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CodaPhone\naid: codaphone-app\nurl: https://codaphone.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of a business, you confirm that you are authorised to bind that business,\n    and “you” refers to that business.\nrestricted_uses:\n- summary: Lawful business purposes only\n  text: use the Service only for lawful business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/codaphone-app/eligibility/codaphone-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CodaPhone's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SMS
- Business Texting
- Messaging
- Shared Inbox
- SMS Campaigns
- 10DLC
- Webhooks
- MCP
---
