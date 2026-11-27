---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If acting for an organization, you represent that you have authority to bind it.
    type: business
  minimum_age:
    text: All users, including guests, must be at least 18.
    value: '18'
  restricted_uses:
  - summary: Sensitive Data
    text: You must not upload, enter, display, or store Sensitive Data as defined in the Privacy Policy
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
name: ramus-dev
provenance_date: '2026-11-10'
provider_name: ramus-dev
provider_slug: ramus-dev
slug: ramus-dev-eligibility
source_date: '2026-11-10'
source_filename: ramus-dev-eligibility.yml
source_heading: Eligibility
source_page: https://ramus.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ramus-dev\naid: ramus-dev\nurl: https://ramus.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If acting for an organization, you represent that you have authority to bind it.\nrestricted_uses:\n- summary: Sensitive Data\n  text: You must not upload, enter, display, or store Sensitive Data as defined in the Privacy Policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All users, including guests, must be at least 18.\n"
source_yaml_url: https://artifacts.apis.io/ramus-dev/eligibility/ramus-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ramus-dev's own page on 2026-11-10.
synthetic: false
tags:
- Android
- Emulator
- Cloud
- Developer Tools
---
