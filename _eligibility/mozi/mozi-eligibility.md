---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Mozi makes no representations that the Application is appropriate or available for use in other locations.
  entity_types:
  - text: App Users must be at least 13 years of age to register an Account and use the Application.
    type: individual
  minimum_age:
    text: App Users must be at least 13 years of age to register an Account and use the Application.
    value: '13'
  restricted_uses:
  - summary: Harassment and unsolicited messaging
    text: you agree not to use the Application’s invitation, sharing, or messaging-related features to send unsolicited communications, to harass or abuse others
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
name: Mozi
provenance_date: '2026-11-10'
provider_name: Mozi
provider_slug: mozi
slug: mozi-eligibility
source_date: '2026-11-10'
source_filename: mozi-eligibility.yml
source_heading: Eligibility
source_page: https://mozi.app/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mozi\naid: mozi\nurl: https://mozi.app/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Mozi makes no representations that the Application is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: App Users must be at least 13 years of age to register an Account and use the Application.\nrestricted_uses:\n- summary: Harassment and unsolicited messaging\n  text: you agree not to use the Application’s invitation, sharing, or messaging-related features to send unsolicited\n    communications, to harass or abuse\
  \ others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: App Users must be at least 13 years of age to register an Account and use the Application.\n"
source_yaml_url: https://artifacts.apis.io/mozi/eligibility/mozi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mozi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Network
- Consumer App
- Mobile
- Privacy
- Contacts
- Event
- Location
---
