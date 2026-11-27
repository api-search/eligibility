---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You shall ensure that only your employees or service providers, or the employees or service providers of your wholly or majority owned subsidiaries who have been expressly authorized by you to use the Service
    type: business
  minimum_age:
    text: You shall ensure that all Authorized Users are at or above the age of majority in their jurisdiction.
    value: age of majority
  restricted_uses:
  - summary: Competitors of R! B2B excluded
    text: You may not use the Service if you or any of your Authorized Users are a competitor of R! B2B (as determined by us in our sole discretion).
  - summary: No sending from group distribution emails
    text: Sending of emails from a group distribution email such as hello@ or marketing@ etc.
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
name: RB2B
provenance_date: '2026-11-10'
provider_name: RB2B
provider_slug: rb2b
slug: rb2b-eligibility
source_date: '2026-11-10'
source_filename: rb2b-eligibility.yml
source_heading: Eligibility
source_page: https://www.rb2b.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RB2B\naid: rb2b\nurl: https://www.rb2b.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You shall ensure that only your employees or service providers, or the employees or service providers of\n    your wholly or majority owned subsidiaries who have been expressly authorized by you to use the Service\nrestricted_uses:\n- summary: Competitors of R! B2B excluded\n  text: You may not use the Service if you or any of your Authorized Users are a competitor of R! B2B (as determined\n    by us in our sole discretion).\n\
  - summary: No sending from group distribution emails\n  text: Sending of emails from a group distribution email such as hello@ or marketing@ etc.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You shall ensure that all Authorized Users are at or above the age of majority in their jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/rb2b/eligibility/rb2b-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from RB2B's own page on 2026-11-10.
synthetic: false
tags:
- Identity Resolution
- Visitor Identification
- B2B Data
- Lead Generation
- Sales Intelligence
- Marketing
- Data Enrichment
- LinkedIn Enrichment
- Hashed Email
- Mobile Ad ID
- Firmographics
- Webhook
- Pixel
- AdTech
- Identity Graph
- MCP
---
