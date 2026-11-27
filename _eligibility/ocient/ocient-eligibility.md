---
api_specs:
- filename: ocient-ocient-http-query-api-api-openapi.yml
  format: yaml
  label: Ocient HTTP Query API
  slug: ocient-ocient-http-query-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ocient/openapi/ocient-ocient-http-query-api-api-openapi.yml
- filename: ocient-system-information-rest-endpoints-api-openapi.yml
  format: yaml
  label: Ocient System Information REST Endpoints API
  slug: ocient-system-information-rest-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ocient/openapi/ocient-system-information-rest-endpoints-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: the Website and any portions or Content thereof may not be exported or re-exported (a) into any United States embargoed countries
  entity_types:
  - text: you are of legal age to form a binding contract with Ocient
    type: individual
  - text: you have the authority to enter into the Terms of Use personally or on behalf of the company or other organization you have named as the user
    type: business
  minimum_age:
    text: The Website is not intended for use by minors, and those under the age of 18 should not proceed to use the Website.
    value: '18'
  restricted_uses:
  - summary: Weapons development
    text: the development, design, manufacture or production of missiles, nuclear, chemical or biological weapons
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration for an account is void where the user lacks the eligibility for registration or such registration is otherwise prohibited.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ocient
provenance_date: '2026-11-10'
provider_name: Ocient
provider_slug: ocient
slug: ocient-eligibility
source_date: '2026-11-10'
source_filename: ocient-eligibility.yml
source_heading: Eligibility
source_page: https://ocient.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ocient\naid: ocient\nurl: https://ocient.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: the Website and any portions or Content thereof may not be exported or re-exported (a) into any United States\n    embargoed countries\nentity_types:\n- type: individual\n  text: you are of legal age to form a binding contract with Ocient\n- type: business\n  text: you have the authority to enter into the Terms of Use personally or on behalf of the company or other organization\n    you have named as the user\nrestricted_uses:\n- summary: Weapons development\n  text: the development,\
  \ design, manufacture or production of missiles, nuclear, chemical or biological weapons\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration for an account is void where the user lacks the eligibility for registration or such registration\n    is otherwise prohibited.\nminimum_age:\n  value: '18'\n  text: The Website is not intended for use by minors, and those under the age of 18 should not proceed to use the\n    Website.\n"
source_yaml_url: https://artifacts.apis.io/ocient/eligibility/ocient-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Ocient's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Analytics
- Data Warehouse
- Database
- SQL
- Artificial Intelligence
- Machine Learning
- Big Data
- Geospatial
- A2A
---
