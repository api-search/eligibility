---
api_specs:
- filename: rv-grid-com-openapi-generated.yml
  format: yaml
  label: rv-grid-com API
  slug: rv-grid-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rv-grid-com/openapi/_ae-authored/rv-grid-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If the User is a natural person, the following shall apply: The User may ONLY register on the Platform and/or use the Services if they are of legal age and considered fully legally competent as determined by the applicable laws.'
    type: individual
  - text: Users may be Consumers or Entrepreneurs.
    type: business
  minimum_age:
    text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Services.
    value: '18'
  restricted_uses:
  - summary: No sharing of User Account
    text: The User may not allow any third party to use such User Account.
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
name: rv-grid-com
provenance_date: '2026-11-10'
provider_name: rv-grid-com
provider_slug: rv-grid-com
slug: rv-grid-com-eligibility
source_date: '2026-11-10'
source_filename: rv-grid-com-eligibility.yml
source_heading: Eligibility
source_page: https://rv-grid.com/pro/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rv-grid-com\naid: rv-grid-com\nurl: https://rv-grid.com/pro/policies/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'If the User is a natural person, the following shall apply: The User may ONLY register on the Platform\n    and/or use the Services if they are of legal age and considered fully legally competent as determined by the\n    applicable laws.'\n- type: business\n  text: Users may be Consumers or Entrepreneurs.\nrestricted_uses:\n- summary: No sharing of User Account\n  text: The User may not allow any third party\
  \ to use such User Account.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have\n    the permission of, and be directly supervised by, their parent or guardian to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/rv-grid-com/eligibility/rv-grid-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from rv-grid-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Grid
- JavaScript
- UI Component
- Open Source
- ProVersion
---
