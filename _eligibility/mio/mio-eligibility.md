---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Unsolicited advertising or spam
    text: Upload, post, email, or otherwise transmit any unsolicited or unauthorized advertising, promotional materials, "junk mail," "spam," "chain letters," "pyramid schemes," or any other form of solicitation.
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
name: Mio
provenance_date: '2026-11-10'
provider_name: Mio
provider_slug: mio
slug: mio-eligibility
source_date: '2026-11-10'
source_filename: mio-eligibility.yml
source_heading: Eligibility
source_page: https://www.m.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mio\naid: mio\nurl: https://www.m.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Unsolicited advertising or spam\n  text: Upload, post, email, or otherwise transmit any unsolicited or unauthorized advertising, promotional materials,\n    \"junk mail,\" \"spam,\" \"chain letters,\" \"pyramid schemes,\" or any other form of solicitation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/mio/eligibility/mio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Mio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Collaboration
- Interoperability
- Messaging
- Enterprise
- Directory Sync
- Google Workspace
- Microsoft 365
- Slack
- Zoom
---
