---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer (individually or on behalf of a company, institution, organization, or other entity
    type: individual
  - text: on behalf of a company, institution, organization, or other entity
    type: business
  minimum_age:
    text: “Customer” may not accept these Terms of Service or use the Service if “Customer” is not of legal age to be legally bound by a contract under any applicable law
    value: legal age
  restricted_uses:
  - summary: Safety-critical uses
    text: NONE OF THE PRODUCTS ARE INTENDED FOR USE IN THE OPERATION OF NUCLEAR FACILITIES, LIFE SUPPORT SYSTEMS, EMERGENCY COMMUNICATIONS
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
name: Appcircle
provenance_date: '2026-11-09'
provider_name: Appcircle
provider_slug: appcircle-io
slug: appcircle-io-eligibility
source_date: '2026-11-09'
source_filename: appcircle-io-eligibility.yml
source_heading: Eligibility
source_page: https://appcircle.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appcircle\naid: appcircle-io\nurl: https://appcircle.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Customer (individually or on behalf of a company, institution, organization, or other entity\n- type: business\n  text: on behalf of a company, institution, organization, or other entity\nrestricted_uses:\n- summary: Safety-critical uses\n  text: NONE OF THE PRODUCTS ARE INTENDED FOR USE IN THE OPERATION OF NUCLEAR FACILITIES, LIFE SUPPORT SYSTEMS,\n    EMERGENCY COMMUNICATIONS\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: “Customer” may not accept these Terms of Service or use the Service if “Customer” is not of legal age to\n    be legally bound by a contract under any applicable law\n"
source_yaml_url: https://artifacts.apis.io/appcircle-io/eligibility/appcircle-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Appcircle's own page on 2026-11-09.
synthetic: false
tags:
- Mobile
- CI/CD
- Automation
- iOS
- Android
---
