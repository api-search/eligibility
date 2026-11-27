---
api_specs:
- filename: eanovation-openapi-generated.yml
  format: yaml
  label: Eanovation API
  slug: eanovation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eanovation/openapi/_ae-authored/eanovation-openapi-generated.yml
claim_count: 3
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
  - summary: Sensitive or regulated personal data
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
name: Eanovation
provenance_date: '2026-11-09'
provider_name: Eanovation
provider_slug: eanovation
slug: eanovation-eligibility
source_date: '2026-11-09'
source_filename: eanovation-eligibility.yml
source_heading: Eligibility
source_page: https://www.eano.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eanovation\naid: eanovation\nurl: https://www.eano.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customers located in the United States may enroll in Eano’s Purchasing Program\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of your organization, that organization is deemed to be\n    the Customer\nrestricted_uses:\n- summary: Sensitive or regulated personal data\n  text: Customer agrees that it shall not use the Solution to send or store personal information that is subject\n    to special regulatory\
  \ or contractual handling requirements\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eanovation/eligibility/eanovation-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Eanovation's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Technology
- Data Analytics
- Digital Transformation
---
