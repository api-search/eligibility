---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Subscriber identified on the applicable Order
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No emergency services use
    text: nor should the Services be used to contact emergency service providers including, but not limited to, police departments, fire departments, or hospitals.
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
name: Sent
provenance_date: '2026-11-10'
provider_name: Sent
provider_slug: sent
slug: sent-eligibility
source_date: '2026-11-10'
source_filename: sent-eligibility.yml
source_heading: Eligibility
source_page: https://www.sent.dm/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sent\naid: sent\nurl: https://www.sent.dm/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the Subscriber identified on the applicable Order\nrestricted_uses:\n- summary: No emergency services use\n  text: nor should the Services be used to contact emergency service providers including, but not limited to, police\n    departments, fire departments, or hospitals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sent/eligibility/sent-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Sent's own page on 2026-11-10.
synthetic: false
tags:
- SMS
- WhatsApp
- RCS
- Messaging API
- Communications
- Developer Platform
- Authentication
- Order Notifications
---
