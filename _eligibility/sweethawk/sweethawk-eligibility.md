---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 1.8 "User" means any person purchasing and accessing the Application.
    type: individual
  minimum_age:
    text: By accepting these Terms, users represent they have capacity and will maintain accurate Membership Data.
    value: null
  restricted_uses:
  - summary: Illegal, immoral or unethical use
    text: Users must not use the Application for illegal, immoral, or unethical purposes.
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
name: Sweethawk
provenance_date: '2026-11-10'
provider_name: Sweethawk
provider_slug: sweethawk
slug: sweethawk-eligibility
source_date: '2026-11-10'
source_filename: sweethawk-eligibility.yml
source_heading: Eligibility
source_page: https://sweethawk.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sweethawk\naid: sweethawk\nurl: https://sweethawk.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 1.8 \"User\" means any person purchasing and accessing the Application.\nrestricted_uses:\n- summary: Illegal, immoral or unethical use\n  text: Users must not use the Application for illegal, immoral, or unethical purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By accepting these Terms, users represent they have capacity and will maintain accurate\
  \ Membership Data.\n"
source_yaml_url: https://artifacts.apis.io/sweethawk/eligibility/sweethawk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sweethawk's own page on 2026-11-10.
synthetic: false
tags:
- Zendesk apps
- ITSM
- HR service
- Employee service desk
- Workflow Automation
- Change Management
---
