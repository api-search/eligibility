---
api_specs:
- filename: findigs-applications-api-openapi.yml
  format: yaml
  label: Findigs Applications API
  slug: findigs-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findigs/openapi/findigs-applications-api-openapi.yml
- filename: findigs-groups-api-openapi.yml
  format: yaml
  label: Findigs Groups API
  slug: findigs-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findigs/openapi/findigs-groups-api-openapi.yml
- filename: findigs-listings-api-openapi.yml
  format: yaml
  label: Findigs Listings API
  slug: findigs-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findigs/openapi/findigs-listings-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You represent and warrant that You ... are a resident of the United States, and ... Findigs does not provide Services outside of the United States
  minimum_age:
    text: You are old enough to be considered an adult under the laws of Your state (for most jurisdictions this age is 18 years old)
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: You may access the Services and print pages from the Services only for personal and non-commercial purposes, and not on behalf of or for the benefit of any third party.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information, including Your identity information (e.g., name, Social Security number, and date of birth), may be required prior to the acknowledgement or completion of Your application.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Findigs
provenance_date: '2026-11-09'
provider_name: Findigs
provider_slug: findigs
slug: findigs-eligibility
source_date: '2026-11-09'
source_filename: findigs-eligibility.yml
source_heading: Eligibility
source_page: https://www.findigs.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Findigs\naid: findigs\nurl: https://www.findigs.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You represent and warrant that You ... are a resident of the United States, and ... Findigs does not provide\n    Services outside of the United States\nentity_types: []\nrestricted_uses:\n- summary: Personal use only\n  text: You may access the Services and print pages from the Services only for personal and non-commercial purposes,\n    and not on behalf of or for the benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Verification of information, including Your identity information (e.g., name, Social Security number, and\n    date of birth), may be required prior to the acknowledgement or completion of Your application.\nminimum_age:\n  value: '18'\n  text: You are old enough to be considered an adult under the laws of Your state (for most jurisdictions this age\n    is 18 years old)\n"
source_yaml_url: https://artifacts.apis.io/findigs/eligibility/findigs-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Findigs's own page on 2026-11-09.
synthetic: false
tags:
- rental-screening
- Tenant Screening
- Resident Screening
- rental-application
- Underwriting
- Decisioning
- Identity Verification
- Income Verification
- Credit Check
- Background Checks
- Fraud Prevention
- Property Management
- Real Estate
- PropTech
- FCRA
- Fair Housing
- Webhook
---
