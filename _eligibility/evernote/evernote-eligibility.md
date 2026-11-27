---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Evernote Service is available worldwide, but your data is stored in the United States, as described in our Privacy Policy.
  entity_types:
  - text: If you are using the Evernote Service as part of a Multi-Seat Account (Evernote Enterprise), your use of the Evernote Service is governed by these Terms
    type: business
  minimum_age:
    text: The Evernote Service is not directed to minors, and any use by minors should only be done with the guidance, supervision and consent of their parents, guardians, and/or authorized school officials.
    value: null
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
name: evernote
provenance_date: '2026-11-09'
provider_name: evernote
provider_slug: evernote
slug: evernote-eligibility
source_date: '2026-11-09'
source_filename: evernote-eligibility.yml
source_heading: Eligibility
source_page: https://evernote.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: evernote\naid: evernote\nurl: https://evernote.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Evernote Service is available worldwide, but your data is stored in the United States, as described\n    in our Privacy Policy.\nentity_types:\n- type: business\n  text: If you are using the Evernote Service as part of a Multi-Seat Account (Evernote Enterprise), your use of\n    the Evernote Service is governed by these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: The Evernote Service is not directed to minors, and any use by minors should only be done with the guidance,\n    supervision and consent of their parents, guardians, and/or authorized school officials.\n"
source_yaml_url: https://artifacts.apis.io/evernote/eligibility/evernote-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from evernote's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Note Taking
- Productivity
- Knowledge Management
- Notes
- Content
- Software-as-a-Service
- Sync
---
