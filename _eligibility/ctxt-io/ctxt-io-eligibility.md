---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any person who registers as a user or provides their personal information to our Services represents that they are 13 years of age or older.
    type: individual
  minimum_age:
    text: Our Services are not directed to children younger than 13, and access and use of our Services is only offered to users 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: U.S. sanctions compliance
    text: your use of our Services and or associated services and products is not contrary to applicable U.S. Sanctions. Such use is prohibited
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
name: Context
provenance_date: '2026-11-09'
provider_name: Context
provider_slug: ctxt-io
slug: ctxt-io-eligibility
source_date: '2026-11-09'
source_filename: ctxt-io-eligibility.yml
source_heading: Eligibility
source_page: https://ctxt.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Context\naid: ctxt-io\nurl: https://ctxt.io/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any person who registers as a user or provides their personal information to our Services represents that\n    they are 13 years of age or older.\nrestricted_uses:\n- summary: U.S. sanctions compliance\n  text: your use of our Services and or associated services and products is not contrary to applicable U.S. Sanctions.\n    Such use is prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: Our Services are not directed to children younger than 13, and access and use of our Services is only offered\n    to users 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/ctxt-io/eligibility/ctxt-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Context's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pastebin
- Content Sharing
- MCP
- AI Agents
- Browser Extension
- Developer Tools
---
