---
api_specs:
- filename: cardtonic-auth-api-openapi.yml
  format: yaml
  label: Cardtonic Auth API
  slug: cardtonic-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cardtonic/openapi/cardtonic-auth-api-openapi.yml
- filename: cardtonic-user-api-openapi.yml
  format: yaml
  label: Cardtonic User API
  slug: cardtonic-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cardtonic/openapi/cardtonic-user-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - NG
    - GH
    text: If you are in Nigeria, these Terms are governed by the laws of the Federal Republic of Nigeria. If you are in Ghana, these Terms are governed by the laws of the Republic of Ghana.
  entity_types:
  - text: Not be less than 18 years of age as an individual
    type: individual
  - text: must possess the authority to accept the terms of use on behalf of or if it’s a company.
    type: business
  minimum_age:
    text: Not be less than 18 years of age as an individual
    value: '18'
  restricted_uses:
  - summary: Illegally obtained assets
    text: Attempt to trade in an asset that was not legally obtained by you.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Pass all KYC and compliance requirements.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cardtonic
provenance_date: '2026-11-09'
provider_name: Cardtonic
provider_slug: cardtonic
slug: cardtonic-eligibility
source_date: '2026-11-09'
source_filename: cardtonic-eligibility.yml
source_heading: Eligibility
source_page: https://cardtonic.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cardtonic\naid: cardtonic\nurl: https://cardtonic.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - NG\n  - GH\n  excluded: []\n  text: If you are in Nigeria, these Terms are governed by the laws of the Federal Republic of Nigeria. If you are\n    in Ghana, these Terms are governed by the laws of the Republic of Ghana.\nentity_types:\n- type: individual\n  text: Not be less than 18 years of age as an individual\n- type: business\n  text: must possess the authority to accept the terms of use on behalf of or if it’s a company.\nrestricted_uses:\n- summary: Illegally obtained assets\n  text: Attempt\
  \ to trade in an asset that was not legally obtained by you.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Pass all KYC and compliance requirements.\nminimum_age:\n  value: '18'\n  text: Not be less than 18 years of age as an individual\n"
source_yaml_url: https://artifacts.apis.io/cardtonic/eligibility/cardtonic-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cardtonic's own page on 2026-11-09.
synthetic: false
tags:
- Africa
- Bill Payments
- eSIM
- Finance
- Fintech
- Gift Cards
- Ghana
- Nigeria
- Payments
- Virtual Dollar Cards
---
