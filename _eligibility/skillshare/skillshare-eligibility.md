---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Students and Teachers must be at least 18 years of age to create an account on Skillshare or any Skillshare owned or operated platforms and to use the Services.
    type: individual
  - text: If you accept these Terms on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms
    type: business
  minimum_age:
    text: Students and Teachers must be at least 18 years of age to create an account on Skillshare or any Skillshare owned or operated platforms and to use the Services.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You will use the Service only for lawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must be a human to open an account. Accounts registered by “bots” or other automated methods are not permitted.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Skillshare
provenance_date: '2026-11-10'
provider_name: Skillshare
provider_slug: skillshare
slug: skillshare-eligibility
source_date: '2026-11-10'
source_filename: skillshare-eligibility.yml
source_heading: Eligibility
source_page: https://legal.skillshare.com/hc/en-us/articles/27194932901645-Skillshare-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skillshare\naid: skillshare\nurl: https://legal.skillshare.com/hc/en-us/articles/27194932901645-Skillshare-Terms-of-Service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Students and Teachers must be at least 18 years of age to create an account on Skillshare or any Skillshare\n    owned or operated platforms and to use the Services.\n- type: business\n  text: If you accept these Terms on behalf of a company or other legal entity, you represent and warrant that you\n    have the authority to bind that company or\
  \ other legal entity to these Terms\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You will use the Service only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must be a human to open an account. Accounts registered by “bots” or other automated methods are not\n    permitted.\nminimum_age:\n  value: '18'\n  text: Students and Teachers must be at least 18 years of age to create an account on Skillshare or any Skillshare\n    owned or operated platforms and to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/skillshare/eligibility/skillshare-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Skillshare's own page on 2026-11-10.
synthetic: false
tags:
- E-Learning
- Creative Education
- Video Courses
- Subscription Learning
- Creator Economy
- Skill Development
- Project-Based Learning
- Design Education
- Marketplace
---
