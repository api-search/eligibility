---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all Service features may be available in your country.
  entity_types:
  - text: The Products and Services are intended for use by individuals
    type: individual
  - text: The Products and Services are intended for use by individuals and not by entities or businesses
    type: business
  minimum_age:
    text: Anyone under thirteen (13) years of age
    value: '13'
  restricted_uses:
  - summary: Commercial purposes
    text: using the Services for any commercial purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accounts and subscriptions for Life360 Services must be owned and operated by an individual who provides their, or their child’s, information to Life360 during account registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jiobit
provenance_date: '2026-11-09'
provider_name: Jiobit
provider_slug: jiobit
slug: jiobit-eligibility
source_date: '2026-11-09'
source_filename: jiobit-eligibility.yml
source_heading: Eligibility
source_page: https://legal.corp.life360.com/hc/en-us/articles/16124856472471-Life360-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jiobit\naid: jiobit\nurl: https://legal.corp.life360.com/hc/en-us/articles/16124856472471-Life360-Terms-of-Service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Not all Service features may be available in your country.\nentity_types:\n- type: individual\n  text: The Products and Services are intended for use by individuals\n- type: business\n  text: The Products and Services are intended for use by individuals and not by entities or businesses\nrestricted_uses:\n- summary: Commercial purposes\n  text: using the Services for any commercial purposes\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accounts and subscriptions for Life360 Services must be owned and operated by an individual who provides\n    their, or their child’s, information to Life360 during account registration.\nminimum_age:\n  value: '13'\n  text: Anyone under thirteen (13) years of age\n"
source_yaml_url: https://artifacts.apis.io/jiobit/eligibility/jiobit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Jiobit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GPS Tracking
- Location
- Wearables
- IoT
- Consumer Hardware
- Family Safety
- Pet Tracking
---
