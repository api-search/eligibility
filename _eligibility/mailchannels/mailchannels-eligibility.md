---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company, organization or another legal entity (an “Entity”), you are agreeing to this Agreement for that Entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned parties
    text: You may not use the Service for any reason if you or any party that owns or controls you, are subject to sanctions or otherwise designated on any list of prohibited or restricted parties
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
name: MailChannels
provenance_date: '2026-11-10'
provider_name: MailChannels
provider_slug: mailchannels
slug: mailchannels-eligibility
source_date: '2026-11-10'
source_filename: mailchannels-eligibility.yml
source_heading: Eligibility
source_page: https://www.mailchannels.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MailChannels\naid: mailchannels\nurl: https://www.mailchannels.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, organization or another legal entity (an\n    “Entity”), you are agreeing to this Agreement for that Entity\nrestricted_uses:\n- summary: Sanctioned parties\n  text: You may not use the Service for any reason if you or any party that owns or controls you, are subject to\n    sanctions or otherwise designated on any list of\
  \ prohibited or restricted parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mailchannels/eligibility/mailchannels-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from MailChannels's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- SMTP
- Platform
---
