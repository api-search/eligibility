---
api_specs:
- filename: raute-io-drivers-api-openapi.yml
  format: yaml
  label: raute-io Drivers API
  slug: raute-io-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raute-io/openapi/raute-io-drivers-api-openapi.yml
- filename: raute-io-orders-api-openapi.yml
  format: yaml
  label: raute-io Orders API
  slug: raute-io-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raute-io/openapi/raute-io-orders-api-openapi.yml
- filename: raute-io-tracking-api-openapi.yml
  format: yaml
  label: raute-io Tracking API
  slug: raute-io-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raute-io/openapi/raute-io-tracking-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To use the Service, you must meet all of the following requirements: Be at least 18 years of age. Have the legal capacity to enter into a binding agreement.'
    type: individual
  minimum_age:
    text: Be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Users prohibited by law
    text: Not be prohibited from using the Service under any applicable law or regulation.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Provide accurate and complete registration information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: raute-io
provenance_date: '2026-11-10'
provider_name: raute-io
provider_slug: raute-io
slug: raute-io-eligibility
source_date: '2026-11-10'
source_filename: raute-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.raute.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: raute-io\naid: raute-io\nurl: https://www.raute.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To use the Service, you must meet all of the following requirements: Be at least 18 years of age. Have\n    the legal capacity to enter into a binding agreement.'\nrestricted_uses:\n- summary: Users prohibited by law\n  text: Not be prohibited from using the Service under any applicable law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Provide accurate and complete registration information.\n\
  minimum_age:\n  value: '18'\n  text: Be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/raute-io/eligibility/raute-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from raute-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Delivery
- Route Planning
- Artificial Intelligence
- Fleet Management
---
