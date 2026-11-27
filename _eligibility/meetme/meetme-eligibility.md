---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use MeetMe where prohibited by law. Users must not be located in a jurisdiction where access is prohibited by applicable law or subject to U.S. or other sovereign sanctions or embargoes.
  entity_types:
  - text: Companies and other organizations may not become Users of MeetMe nor use MeetMe without our express written approval.
    type: business
  minimum_age:
    text: You must be at least 18 years old to register for MeetMe.
    value: '18'
  restricted_uses:
  - summary: No commercial activity
    text: You may not use MeetMe in connection with any commercial activity without our express written approval.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may require you to verify your age or identity in order to register for, access, or continue using the Services. Verification may include providing personal information, photographs or videos (including biometric data), or government-issued identity documents.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MeetMe
provenance_date: '2026-11-10'
provider_name: MeetMe
provider_slug: meetme
slug: meetme-eligibility
source_date: '2026-11-10'
source_filename: meetme-eligibility.yml
source_heading: Eligibility
source_page: https://www.meetme.com/en/termsandconditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MeetMe\naid: meetme\nurl: https://www.meetme.com/en/termsandconditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may not use MeetMe where prohibited by law. Users must not be located in a jurisdiction where access\n    is prohibited by applicable law or subject to U.S. or other sovereign sanctions or embargoes.\nentity_types:\n- type: business\n  text: Companies and other organizations may not become Users of MeetMe nor use MeetMe without our express written\n    approval.\nrestricted_uses:\n- summary: No commercial activity\n  text: You may not use\
  \ MeetMe in connection with any commercial activity without our express written approval.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may require you to verify your age or identity in order to register for, access, or continue using the\n    Services. Verification may include providing personal information, photographs or videos (including biometric\n    data), or government-issued identity documents.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register for MeetMe.\n"
source_yaml_url: https://artifacts.apis.io/meetme/eligibility/meetme-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from MeetMe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social
- Social Network
- Dating
- Messaging
- Live Streaming
- Consumer
---
