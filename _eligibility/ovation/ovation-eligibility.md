---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not a resident of any country which is subject to currently-ongoing sanctions imposed by the United States of America or the United Nations
  minimum_age:
    text: you may not access or use the SERVICES or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Acceptable Use Policy restrictions
    text: 'You agree not to use the Services to collect, upload, transmit, display, or distribute any User Content or to take any action that: (i) violates any third-party right'
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
name: Ovation
provenance_date: '2026-11-10'
provider_name: Ovation
provider_slug: ovation
slug: ovation-eligibility
source_date: '2026-11-10'
source_filename: ovation-eligibility.yml
source_heading: Eligibility
source_page: https://ovationup.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ovation\naid: ovation\nurl: https://ovationup.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not a resident of any country which is subject to currently-ongoing sanctions\n    imposed by the United States of America or the United Nations\nentity_types: []\nrestricted_uses:\n- summary: Acceptable Use Policy restrictions\n  text: 'You agree not to use the Services to collect, upload, transmit, display, or distribute any User Content\n    or to take any action that: (i) violates any third-party right'\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the SERVICES or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/ovation/eligibility/ovation-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ovation's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Guest Feedback
- Guest Experience
- Reputation Management
- SMS Marketing
- Analytics
---
