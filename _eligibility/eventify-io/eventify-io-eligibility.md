---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"You," "Your," and "Client" refer to event organizers using Eventify.'
    type: other
  minimum_age:
    text: Eventify is intended for users over 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Excluded event categories
    text: We do not accept apps for political, social, gambling, entertainment, finance, or bitcoin-related events.
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
name: Eventify
provenance_date: '2026-11-09'
provider_name: Eventify
provider_slug: eventify-io
slug: eventify-io-eligibility
source_date: '2026-11-09'
source_filename: eventify-io-eligibility.yml
source_heading: Eligibility
source_page: https://eventify.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eventify\naid: eventify-io\nurl: https://eventify.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: '\"You,\" \"Your,\" and \"Client\" refer to event organizers using Eventify.'\nrestricted_uses:\n- summary: Excluded event categories\n  text: We do not accept apps for political, social, gambling, entertainment, finance, or bitcoin-related events.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Eventify is intended for users over 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/eventify-io/eligibility/eventify-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Eventify's own page on 2026-11-09.
synthetic: false
tags:
- Event Management
- Artificial Intelligence
- Software
- Platform
- Conferences
- Hybrid Events
---
