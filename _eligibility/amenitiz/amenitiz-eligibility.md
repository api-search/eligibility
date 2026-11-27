---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Persons of legal age at the place where they subscribe to or use the Services
    type: individual
  - text: Self-employed professionals or companies in the hospitality industry.
    type: business
  minimum_age:
    text: Persons of legal age at the place where they subscribe to or use the Services
    value: legal age
  restricted_uses:
  - summary: AmenitizPay own business only
    text: the right to use the AmenitizPay Service applies only to hospitality business and related activities made on its own behalf.
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
name: Amenitiz
provenance_date: '2026-11-09'
provider_name: Amenitiz
provider_slug: amenitiz
slug: amenitiz-eligibility
source_date: '2026-11-09'
source_filename: amenitiz-eligibility.yml
source_heading: Eligibility
source_page: https://amenitiz.com/en/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amenitiz\naid: amenitiz\nurl: https://amenitiz.com/en/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Persons of legal age at the place where they subscribe to or use the Services\n- type: business\n  text: Self-employed professionals or companies in the hospitality industry.\nrestricted_uses:\n- summary: AmenitizPay own business only\n  text: the right to use the AmenitizPay Service applies only to hospitality business and related activities made\n    on its own behalf.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: Persons of legal age at the place where they subscribe to or use the Services\n"
source_yaml_url: https://artifacts.apis.io/amenitiz/eligibility/amenitiz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Amenitiz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hospitality
- Hotel Management
- Property Management
- PMS
- Booking Engine
- Channel Manager
- Payments
- Travel
- Software-as-a-Service
---
