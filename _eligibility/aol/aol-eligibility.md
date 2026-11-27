---
api_specs:
- filename: aol-openid-connect-api-openapi.yml
  format: yaml
  label: AOL OpenID Connect API
  slug: aol-openid-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aol/openapi/aol-openid-connect-api-openapi.yml
- filename: aol-oauth2-api-openapi.yml
  format: yaml
  label: AOL O Auth2 API
  slug: aol-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aol/openapi/aol-oauth2-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all Services or features may be available in all countries or regions
  entity_types:
  - text: If you are using the Services on behalf of a company, business or other entity, you represent that you have the legal authority to accept these Terms on behalf of that entity
    type: business
  minimum_age:
    text: 'Minimum Age: 13 years old'
    value: '13'
  restricted_uses:
  - summary: Weapons end uses
    text: will not use the Services for military, nuclear, missile, chemical or biological weaponry end uses
  - summary: Material support to designated terrorist organizations
    text: You agree to not use the Services to provide material support or resources
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
name: AOL
provenance_date: '2026-11-09'
provider_name: AOL
provider_slug: aol
slug: aol-eligibility
source_date: '2026-11-09'
source_filename: aol-eligibility.yml
source_heading: Eligibility
source_page: https://legal.aol.com/terms/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AOL\naid: aol\nurl: https://legal.aol.com/terms/index.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Not all Services or features may be available in all countries or regions\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a company, business or other entity, you represent that you have\n    the legal authority to accept these Terms on behalf of that entity\nrestricted_uses:\n- summary: Weapons end uses\n  text: will not use the Services for military, nuclear, missile, chemical or biological weaponry end uses\n- summary:\
  \ Material support to designated terrorist organizations\n  text: You agree to not use the Services to provide material support or resources\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: 'Minimum Age: 13 years old'\n"
source_yaml_url: https://artifacts.apis.io/aol/eligibility/aol-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AOL's own page on 2026-11-09.
synthetic: false
tags:
- Digital Media
- News
- Entertainment
- Advertising
- Identity
- OpenID Connect
- Authentication
- Email
- Consumer Internet
- Fortune 1000
---
