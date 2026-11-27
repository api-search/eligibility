---
api_specs:
- filename: ebsco-content-api-openapi.yml
  format: yaml
  label: EBSCO Content API
  slug: ebsco-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ebsco/openapi/ebsco-content-api-openapi.yml
- filename: ebsco-publishers-api-openapi.yml
  format: yaml
  label: EBSCO Publishers API
  slug: ebsco-publishers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ebsco/openapi/ebsco-publishers-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representations that the Website and its content are appropriate or available for use in all locations. Use of or access to the Website may not be legal by certain persons or in certain countries.
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: EBSCO
provenance_date: '2026-11-09'
provider_name: EBSCO
provider_slug: ebsco
slug: ebsco-eligibility
source_date: '2026-11-09'
source_filename: ebsco-eligibility.yml
source_heading: Eligibility
source_page: https://legal.ebsco.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EBSCO\naid: ebsco\nurl: https://legal.ebsco.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representations that the Website and its content are appropriate or available for use in all\n    locations. Use of or access to the Website may not be legal by certain persons or in certain countries.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/ebsco/eligibility/ebsco-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from EBSCO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Research
- Library
- Education
- Information
---
