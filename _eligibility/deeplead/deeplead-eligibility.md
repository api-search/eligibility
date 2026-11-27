---
api_specs:
- filename: deeplead-account-api-openapi.yml
  format: yaml
  label: Deeplead Account API
  slug: deeplead-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-account-api-openapi.yml
- filename: deeplead-businesses-api-openapi.yml
  format: yaml
  label: Deeplead Businesses API
  slug: deeplead-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-businesses-api-openapi.yml
- filename: deeplead-contacts-api-openapi.yml
  format: yaml
  label: Deeplead Contacts API
  slug: deeplead-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-contacts-api-openapi.yml
- filename: deeplead-deliverability-api-openapi.yml
  format: yaml
  label: Deeplead Deliverability API
  slug: deeplead-deliverability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-deliverability-api-openapi.yml
- filename: deeplead-organizations-api-openapi.yml
  format: yaml
  label: Deeplead Organizations API
  slug: deeplead-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-organizations-api-openapi.yml
- filename: deeplead-persons-api-openapi.yml
  format: yaml
  label: Deeplead Persons API
  slug: deeplead-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-persons-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for your personal or internal business purposes
    type: individual
  - text: solely for your personal or internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Outreach must follow law and honour opt-outs
    text: Customers who use Deeplead to contact businesses must follow applicable law (including CAN-SPAM, GDPR and the German UWG) and honour every opt-out immediately.
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
name: Deeplead
provenance_date: '2026-11-09'
provider_name: Deeplead
provider_slug: deeplead
slug: deeplead-eligibility
source_date: '2026-11-09'
source_filename: deeplead-eligibility.yml
source_heading: Eligibility
source_page: https://www.deeplead.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deeplead\naid: deeplead\nurl: https://www.deeplead.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: solely for your personal or internal business purposes\n- type: business\n  text: solely for your personal or internal business purposes\nrestricted_uses:\n- summary: Outreach must follow law and honour opt-outs\n  text: Customers who use Deeplead to contact businesses must follow applicable law (including CAN-SPAM, GDPR and\n    the German UWG) and honour every opt-out immediately.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deeplead/eligibility/deeplead-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Deeplead's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lead Generation
- Cold Email
- Artificial Intelligence
- Sales Automation
---
