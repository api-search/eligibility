---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to register for Skout.
    type: individual
  - text: Companies and other organizations may not become Users of Skout nor use Skout without our express written approval.
    type: business
  minimum_age:
    text: You must be at least 18 years old to register for Skout.
    value: '18'
  restricted_uses:
  - summary: Prohibited jurisdictions
    text: You may not use Skout where prohibited by law, and you agree to comply with all local rules regarding online conduct and acceptable content.
  - summary: Commercial use
    text: You may not use Skout in connection with any commercial activity without our express written approval.
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
name: Skout
provenance_date: '2026-11-10'
provider_name: Skout
provider_slug: skout
slug: skout-eligibility
source_date: '2026-11-10'
source_filename: skout-eligibility.yml
source_heading: Eligibility
source_page: https://www.skout.com/en/termsandconditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skout\naid: skout\nurl: https://www.skout.com/en/termsandconditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to register for Skout.\n- type: business\n  text: Companies and other organizations may not become Users of Skout nor use Skout without our express written\n    approval.\nrestricted_uses:\n- summary: Prohibited jurisdictions\n  text: You may not use Skout where prohibited by law, and you agree to comply with all local rules regarding online\n    conduct and acceptable\
  \ content.\n- summary: Commercial use\n  text: You may not use Skout in connection with any commercial activity without our express written approval.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register for Skout.\n"
source_yaml_url: https://artifacts.apis.io/skout/eligibility/skout-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Skout's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social
- Dating
- Consumer App
- Mobile
- Messaging
- Social Network
---
