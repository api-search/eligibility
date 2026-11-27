---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer user, please note that we only provide our site for domestic and private use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Domestic and private use only for consumers
    text: You agree not to use our site for any commercial or business purposes
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
name: Spamhaus
provenance_date: '2026-11-10'
provider_name: Spamhaus
provider_slug: spamhaus
slug: spamhaus-eligibility
source_date: '2026-11-10'
source_filename: spamhaus-eligibility.yml
source_heading: Eligibility
source_page: https://www.spamhaus.org/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spamhaus\naid: spamhaus\nurl: https://www.spamhaus.org/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer user, please note that we only provide our site for domestic and private use.\nrestricted_uses:\n- summary: Domestic and private use only for consumers\n  text: You agree not to use our site for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spamhaus/eligibility/spamhaus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Spamhaus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Anti-Spam
- Reputation
- DNSBL
---
