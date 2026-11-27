---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: You are in compliance with all laws and regulations of India when you access and use the Services.
  entity_types:
  - text: You confirm that you are at least 18 years old and have the legal capacity to understand, accept, and comply with these Terms.
    type: individual
  - text: or any legal entity that books Pro Services (defined below) on behalf of end-users
    type: business
  minimum_age:
    text: You confirm that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: The Platform is for your personal and non-commercial use only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be required to furnish certain details, including but not limited to your name, e-mail address, and phone number and such other information or documentation as may be required for identity verification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pronto
provenance_date: '2026-11-10'
provider_name: Pronto
provider_slug: pronto
slug: pronto-eligibility
source_date: '2026-11-10'
source_filename: pronto-eligibility.yml
source_heading: Eligibility
source_page: https://www.withpronto.com/tnc/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pronto\naid: pronto\nurl: https://www.withpronto.com/tnc/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: You are in compliance with all laws and regulations of India when you access and use the Services.\nentity_types:\n- type: individual\n  text: You confirm that you are at least 18 years old and have the legal capacity to understand, accept, and comply\n    with these Terms.\n- type: business\n  text: or any legal entity that books Pro Services (defined below) on behalf of end-users\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: The Platform is for\
  \ your personal and non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may be required to furnish certain details, including but not limited to your name, e-mail address,\n    and phone number and such other information or documentation as may be required for identity verification\nminimum_age:\n  value: '18'\n  text: You confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/pronto/eligibility/pronto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Pronto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- Home Services
- On-Demand
- Marketplace
- Household Services
- Mobile App
- India
---
