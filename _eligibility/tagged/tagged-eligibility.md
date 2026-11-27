---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use Tagged where prohibited by law, and you agree to comply with all local rules regarding online conduct and acceptable content.
  entity_types:
  - text: Tagged is for your personal use only and you may not use it for any other purpose.
    type: individual
  - text: Companies and other organizations may not become Users of Tagged nor use Tagged without our express written approval.
    type: business
  minimum_age:
    text: You must be at least 18 years old to register for Tagged.
    value: '18'
  restricted_uses:
  - summary: Commercial activity
    text: You may not use Tagged in connection with any commercial activity without our express written approval.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may require you to verify your age or identity in order to register for, access, or continue using the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tagged
provenance_date: '2026-11-10'
provider_name: Tagged
provider_slug: tagged
slug: tagged-eligibility
source_date: '2026-11-10'
source_filename: tagged-eligibility.yml
source_heading: Eligibility
source_page: https://www.tagged.com/en/termsandconditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tagged\naid: tagged\nurl: https://www.tagged.com/en/termsandconditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may not use Tagged where prohibited by law, and you agree to comply with all local rules regarding online\n    conduct and acceptable content.\nentity_types:\n- type: individual\n  text: Tagged is for your personal use only and you may not use it for any other purpose.\n- type: business\n  text: Companies and other organizations may not become Users of Tagged nor use Tagged without our express written\n    approval.\nrestricted_uses:\n- summary:\
  \ Commercial activity\n  text: You may not use Tagged in connection with any commercial activity without our express written approval.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may require you to verify your age or identity in order to register for, access, or continue using the\n    Services.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register for Tagged.\n"
source_yaml_url: https://artifacts.apis.io/tagged/eligibility/tagged-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Tagged's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Network
- Social Discovery
- Online Dating
- Consumer
- Messaging
- Mobile App
---
