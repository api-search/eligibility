---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is available only to individuals and entities who can form legally binding contracts under applicable law.
    type: individual
  - text: The Site is available only to individuals and entities who can form legally binding contracts under applicable law.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use by prohibited or excluded persons
    text: You agree to use all reasonable efforts not to arrange for any of these prohibited persons or excluded persons to stay at, use or tour any Wynn facilities or use any Wynn services including the Site.
  - summary: Self-excluded persons may not use the Site
    text: Persons who have executed and submitted to Wynn a Request for Voluntary Self-Exclusion from Casino Gambling ("Voluntary Self-Exclusion") may not use the Site.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Wynn reserves the right to deny access and/or registration to the Site to anyone at any time in its sole and absolute discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wynn Resorts
provenance_date: '2026-11-10'
provider_name: Wynn Resorts
provider_slug: wynn-resorts
slug: wynn-resorts-eligibility
source_date: '2026-11-10'
source_filename: wynn-resorts-eligibility.yml
source_heading: Eligibility
source_page: https://www.wynnlasvegas.com/terms-and-conditions/708708
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wynn Resorts\naid: wynn-resorts\nurl: https://www.wynnlasvegas.com/terms-and-conditions/708708\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is available only to individuals and entities who can form legally binding contracts under applicable\n    law.\n- type: business\n  text: The Site is available only to individuals and entities who can form legally binding contracts under applicable\n    law.\nrestricted_uses:\n- summary: No use by prohibited or excluded persons\n  text: You agree to use all reasonable efforts not to\
  \ arrange for any of these prohibited persons or excluded persons\n    to stay at, use or tour any Wynn facilities or use any Wynn services including the Site.\n- summary: Self-excluded persons may not use the Site\n  text: Persons who have executed and submitted to Wynn a Request for Voluntary Self-Exclusion from Casino Gambling\n    (\"Voluntary Self-Exclusion\") may not use the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Wynn reserves the right to deny access and/or registration to the Site to anyone at any time in its sole\n    and absolute discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wynn-resorts/eligibility/wynn-resorts-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Wynn Resorts's own page on 2026-11-10.
synthetic: false
tags:
- Fortune 500
---
