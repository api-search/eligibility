---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Services are offered only for your personal use, and not for the use or benefit of any third party.
    type: individual
  minimum_age:
    text: In the U.S., you must be at least 16 years of age to use the Services.
    value: '16'
  restricted_uses:
  - summary: Personal use only
    text: the Services are offered only for your personal use, and not for the use or benefit of any third party.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may, in our sole discretion, refuse to offer the Services to any person or entity for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BuzzFeed
provenance_date: '2026-11-09'
provider_name: BuzzFeed
provider_slug: buzzfeed
slug: buzzfeed-eligibility
source_date: '2026-11-09'
source_filename: buzzfeed-eligibility.yml
source_heading: Eligibility
source_page: https://www.buzzfeed.com/about/useragreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuzzFeed\naid: buzzfeed\nurl: https://www.buzzfeed.com/about/useragreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the Services are offered only for your personal use, and not for the use or benefit of any third party.\nrestricted_uses:\n- summary: Personal use only\n  text: the Services are offered only for your personal use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may, in our sole discretion, refuse to offer the Services to any person\
  \ or entity for any reason.\nminimum_age:\n  value: '16'\n  text: In the U.S., you must be at least 16 years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/buzzfeed/eligibility/buzzfeed-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from BuzzFeed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Publishing
- News
- Entertainment
- Content
- Advertising
---
