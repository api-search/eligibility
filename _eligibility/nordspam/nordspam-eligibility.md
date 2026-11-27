---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All IP addresses and domains that are added to the reputation database are manually moderated to prevent false positives.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NordSpam
provenance_date: '2026-11-10'
provider_name: NordSpam
provider_slug: nordspam
slug: nordspam-eligibility
source_date: '2026-11-10'
source_filename: nordspam-eligibility.yml
source_heading: Eligibility
source_page: https://www.nordspam.com/policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NordSpam\naid: nordspam\nurl: https://www.nordspam.com/policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All IP addresses and domains that are added to the reputation database are manually moderated to prevent\n    false positives.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nordspam/eligibility/nordspam-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from NordSpam's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Spam
- DNSBL
- Security
- Email
- Reputation
---
