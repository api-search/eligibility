---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual who is at least 16 years old.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use the services.
    value: '16'
  restricted_uses:
  - summary: Internal personal use only
    text: You will only use the Services for your own internal, personal use, and not on behalf of or for the benefit of any third party
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
name: About.me
provenance_date: '2026-11-09'
provider_name: About.me
provider_slug: aboutme
slug: aboutme-eligibility
source_date: '2026-11-09'
source_filename: aboutme-eligibility.yml
source_heading: Eligibility
source_page: https://about.me/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: About.me\naid: aboutme\nurl: https://about.me/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual who is at least 16 years old.\nrestricted_uses:\n- summary: Internal personal use only\n  text: You will only use the Services for your own internal, personal use, and not on behalf of or for the benefit\n    of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years\
  \ old to use the services.\n"
source_yaml_url: https://artifacts.apis.io/aboutme/eligibility/aboutme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from About.me's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Personal Website
- Online Identity
- Profile Page
- Personal Branding
- Website Builder
- Landing Pages
- Portfolio
- Artificial Intelligence
- Lead Capture
---
