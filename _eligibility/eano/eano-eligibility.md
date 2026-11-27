---
api_specs:
- filename: eano-openapi-generated.yml
  format: yaml
  label: Eano API
  slug: eano-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eano/openapi/_ae-authored/eano-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customers located in the United States may enroll in Eano’s Purchasing Program
  entity_types:
  - text: If you are entering into this Agreement on behalf of your organization, that organization is deemed to be the Customer
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred from access
    text: Eano’s direct competitors may not access the Solution or Services.
  - summary: Sensitive personal information prohibited
    text: Customer agrees that it shall not use the Solution to send or store personal information that is subject to special regulatory or contractual handling requirements
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
name: Eano
provenance_date: '2026-11-09'
provider_name: Eano
provider_slug: eano
slug: eano-eligibility
source_date: '2026-11-09'
source_filename: eano-eligibility.yml
source_heading: Eligibility
source_page: https://www.eano.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eano\naid: eano\nurl: https://www.eano.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customers located in the United States may enroll in Eano’s Purchasing Program\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of your organization, that organization is deemed to be\n    the Customer\nrestricted_uses:\n- summary: Direct competitors barred from access\n  text: Eano’s direct competitors may not access the Solution or Services.\n- summary: Sensitive personal information prohibited\n  text: Customer\
  \ agrees that it shall not use the Solution to send or store personal information that is subject\n    to special regulatory or contractual handling requirements\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eano/eligibility/eano-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Eano's own page on 2026-11-09.
synthetic: false
tags:
- Construction
- Software-as-a-Service
- Project Management
- Artificial Intelligence
- Residential
---
