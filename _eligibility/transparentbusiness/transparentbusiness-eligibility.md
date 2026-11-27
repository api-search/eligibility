---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are of sufficient age to register for an account on TB; to access the Websites and Services you must be at least 18 years of age.
    type: individual
  - text: You hold the authority and/or sufficient legal representation to register for any kind of entity, when applicable.
    type: business
  minimum_age:
    text: to access the Websites and Services you must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No false identities
    text: You are not using or planning to use or exploit false identities, impersonate any other person
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: At the time of registration, you state to have entered true and verifiable information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TransparentBusiness
provenance_date: '2026-11-10'
provider_name: TransparentBusiness
provider_slug: transparentbusiness
slug: transparentbusiness-eligibility
source_date: '2026-11-10'
source_filename: transparentbusiness-eligibility.yml
source_heading: Eligibility
source_page: https://transparentbusiness.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TransparentBusiness\naid: transparentbusiness\nurl: https://transparentbusiness.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are of sufficient age to register for an account on TB; to access the Websites and Services you must\n    be at least 18 years of age.\n- type: business\n  text: You hold the authority and/or sufficient legal representation to register for any kind of entity, when applicable.\nrestricted_uses:\n- summary: No false identities\n  text: You are not using or planning to use or exploit false\
  \ identities, impersonate any other person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: At the time of registration, you state to have entered true and verifiable information.\nminimum_age:\n  value: '18'\n  text: to access the Websites and Services you must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/transparentbusiness/eligibility/transparentbusiness-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from TransparentBusiness's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Remote Work
- Workforce Management
- Time Tracking
- Productivity
- Project Management
- Human Resources
- Software-as-a-Service
---
