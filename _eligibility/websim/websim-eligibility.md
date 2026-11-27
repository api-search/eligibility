---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering for our Platform on behalf of an organization, you warrant that you are authorized to agree to this Agreement on their behalf.
    type: business
  minimum_age:
    text: Our Platform are not intended for children under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Children under 13
    text: Our Platform are not intended for children under the age of 13.
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
name: Websim
provenance_date: '2026-11-10'
provider_name: Websim
provider_slug: websim
slug: websim-eligibility
source_date: '2026-11-10'
source_filename: websim-eligibility.yml
source_heading: Eligibility
source_page: https://websim.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Websim\naid: websim\nurl: https://websim.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering for our Platform on behalf of an organization, you warrant that you are authorized\n    to agree to this Agreement on their behalf.\nrestricted_uses:\n- summary: Children under 13\n  text: Our Platform are not intended for children under the age of 13.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our Platform are not intended for children under\
  \ the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/websim/eligibility/websim-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Websim's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
