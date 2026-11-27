---
api_specs:
- filename: api-docs.zomentum.com
  format: yaml
  label: Zomentum API
  slug: zomentum-api
  spec_type: Postman
  url: https://api-docs.zomentum.com
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You confirm you are not located in an embargoed country or on a U.S. government restricted-party list.
  entity_types:
  - text: The Service is for business use only.
    type: business
  minimum_age:
    text: Users must be at least 18.
    value: '18'
  restricted_uses:
  - summary: Payment Services limited to own products and services
    text: You may use Payment Services only to collect payment for your own products and services, as described in your application.
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
name: Zomentum
provenance_date: '2026-11-10'
provider_name: Zomentum
provider_slug: zomentum
slug: zomentum-eligibility
source_date: '2026-11-10'
source_filename: zomentum-eligibility.yml
source_heading: Eligibility
source_page: https://www.zomentum.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zomentum\naid: zomentum\nurl: https://www.zomentum.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You confirm you are not located in an embargoed country or on a U.S. government restricted-party list.\nentity_types:\n- type: business\n  text: The Service is for business use only.\nrestricted_uses:\n- summary: Payment Services limited to own products and services\n  text: You may use Payment Services only to collect payment for your own products and services, as described in\n    your application.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must be at least 18.\n"
source_yaml_url: https://artifacts.apis.io/zomentum/eligibility/zomentum-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zomentum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- MSP
- CRM
- Sales
- Proposals
- Payments
- Revenue Platform
- PSA Integration
---
