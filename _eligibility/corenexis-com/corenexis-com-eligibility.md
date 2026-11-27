---
api_specs:
- filename: corenexis-com-openapi-generated.yml
  format: yaml
  label: corenexis-com API
  slug: corenexis-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corenexis-com/openapi/_ae-authored/corenexis-com-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Services are available globally, subject to applicable law and to the payment methods supported in your region.
  entity_types:
  - text: You are at least 18 years of age, or the age of majority in your jurisdiction, and are legally able to enter into a binding contract
    type: individual
  - text: Accounts are for a single user or a single organisation and may not be resold or shared
    type: business
  minimum_age:
    text: You are at least 18 years of age, or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Strictly prohibited content
    text: Child sexual abuse material (CSAM)
  - summary: Illegal purposes
    text: You will not use the Services for any illegal or unauthorised purpose
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
name: corenexis-com
provenance_date: '2026-11-09'
provider_name: corenexis-com
provider_slug: corenexis-com
slug: corenexis-com-eligibility
source_date: '2026-11-09'
source_filename: corenexis-com-eligibility.yml
source_heading: Eligibility
source_page: https://corenexis.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: corenexis-com\naid: corenexis-com\nurl: https://corenexis.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Our Services are available globally, subject to applicable law and to the payment methods supported in your\n    region.\nentity_types:\n- type: individual\n  text: You are at least 18 years of age, or the age of majority in your jurisdiction, and are legally able to enter\n    into a binding contract\n- type: business\n  text: Accounts are for a single user or a single organisation and may not be resold or shared\nrestricted_uses:\n- summary:\
  \ Strictly prohibited content\n  text: Child sexual abuse material (CSAM)\n- summary: Illegal purposes\n  text: You will not use the Services for any illegal or unauthorised purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age, or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/corenexis-com/eligibility/corenexis-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from corenexis-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Platform
- Developer Tools
- Fintech
- Software-as-a-Service
---
