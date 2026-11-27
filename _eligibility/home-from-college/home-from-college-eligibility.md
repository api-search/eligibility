---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Account terminated or suspended
    text: You may not use H\FC if we have terminated or suspended your account, or banned you.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Home From College
provenance_date: '2026-11-09'
provider_name: Home From College
provider_slug: home-from-college
slug: home-from-college-eligibility
source_date: '2026-11-09'
source_filename: home-from-college-eligibility.yml
source_heading: Eligibility
source_page: https://homefromcollege.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Home From College\naid: home-from-college\nurl: https://homefromcollege.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Account terminated or suspended\n  text: You may not use H\\FC if we have terminated or suspended your account, or banned you.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/home-from-college/eligibility/home-from-college-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Home From College's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Marketplace
- Gen Z
- Creator Economy
- Gig Economy
- Students
- Marketing
- Influencer Marketing
---
