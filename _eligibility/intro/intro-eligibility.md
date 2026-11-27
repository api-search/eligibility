---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are neither located in a sanctioned country nor a prohibited person.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Memberships not for resale
    text: Intro Memberships are intended and authorized only for personal, non-transferrable, not-for-resale use only.
  - summary: Emergency situations
    text: EMERGENCY QUESTIONS AND CRISIS SITUATIONS (particularly regarding medical or mental health issues) should not be directed to the Site
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
name: Intro
provenance_date: '2026-11-09'
provider_name: Intro
provider_slug: intro
slug: intro-eligibility
source_date: '2026-11-09'
source_filename: intro-eligibility.yml
source_heading: Eligibility
source_page: https://intro.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Intro\naid: intro\nurl: https://intro.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are neither located in a sanctioned country nor a prohibited person.\nentity_types: []\nrestricted_uses:\n- summary: Memberships not for resale\n  text: Intro Memberships are intended and authorized only for personal, non-transferrable, not-for-resale use only.\n- summary: Emergency situations\n  text: EMERGENCY QUESTIONS AND CRISIS SITUATIONS (particularly regarding medical or mental health issues) should\n    not be directed to the Site\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/intro/eligibility/intro-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Intro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Experts
- Video Calls
- Consumer
- Booking
- Creator Economy
- Scheduling
---
