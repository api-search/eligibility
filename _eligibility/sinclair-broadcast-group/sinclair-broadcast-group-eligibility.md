---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Children under the age of 16 may not register for the Service.
    value: '16'
  restricted_uses:
  - summary: Personal advertising age limit
    text: Personal advertising participants must be 18 years or older.
  - summary: Spam and unsolicited bulk email
    text: We will immediately terminate any account which we believe is being used to transmit, or is otherwise connected with, any spam or other unsolicited bulk email
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
name: Sinclair
provenance_date: '2026-11-10'
provider_name: Sinclair
provider_slug: sinclair-broadcast-group
slug: sinclair-broadcast-group-eligibility
source_date: '2026-11-10'
source_filename: sinclair-broadcast-group-eligibility.yml
source_heading: Eligibility
source_page: https://sbgi.net/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sinclair\naid: sinclair-broadcast-group\nurl: https://sbgi.net/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal advertising age limit\n  text: Personal advertising participants must be 18 years or older.\n- summary: Spam and unsolicited bulk email\n  text: We will immediately terminate any account which we believe is being used to transmit, or is otherwise connected\n    with, any spam or other unsolicited bulk email\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '16'\n  text: Children under the age of 16 may not register for the Service.\n"
source_yaml_url: https://artifacts.apis.io/sinclair-broadcast-group/eligibility/sinclair-broadcast-group-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sinclair's own page on 2026-11-10.
synthetic: false
tags:
- Broadcasting
- Television
- Local News
- Sports Media
- Regional Sports Networks
- Digital Marketing
- AdTech
- NextGen TV
- ATSC 3.0
- Media
---
