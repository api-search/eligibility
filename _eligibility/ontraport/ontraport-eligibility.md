---
api_specs:
- filename: ontraport-metadata-api-openapi.yml
  format: yaml
  label: Ontraport Metadata API
  slug: ontraport-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontraport/openapi/ontraport-metadata-api-openapi.yml
- filename: ontraport-objects-api-openapi.yml
  format: yaml
  label: Ontraport Objects API
  slug: ontraport-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontraport/openapi/ontraport-objects-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 13 years or older to use this Service. You must be a human.
    type: individual
  minimum_age:
    text: You must be 13 years or older to use this Service.
    value: '13'
  restricted_uses:
  - summary: AI decisions with significant effects
    text: Make decisions that produce legal or similarly significant effects on individuals, such as decisions about credit, employment, housing, insurance, or eligibility for services, without meaningful human review
  - summary: Protected health information in AI features
    text: Submit protected health information, as defined under the Health Insurance Portability and Accountability Act, or other sensitive categories of personal data, unless Ontraport has expressly agreed in writing to support that use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your legal full name, a valid email address, and any other information requested in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ontraport
provenance_date: '2026-11-10'
provider_name: Ontraport
provider_slug: ontraport
slug: ontraport-eligibility
source_date: '2026-11-10'
source_filename: ontraport-eligibility.yml
source_heading: Eligibility
source_page: https://ontraport.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ontraport\naid: ontraport\nurl: https://ontraport.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 13 years or older to use this Service. You must be a human.\nrestricted_uses:\n- summary: AI decisions with significant effects\n  text: Make decisions that produce legal or similarly significant effects on individuals, such as decisions about\n    credit, employment, housing, insurance, or eligibility for services, without meaningful human review\n- summary: Protected health information in AI features\n\
  \  text: Submit protected health information, as defined under the Health Insurance Portability and Accountability\n    Act, or other sensitive categories of personal data, unless Ontraport has expressly agreed in writing to support\n    that use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your legal full name, a valid email address, and any other information requested in order\n    to complete the signup process.\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/ontraport/eligibility/ontraport-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Ontraport's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Marketing Automation
- Email Marketing
- E-Commerce
- Landing Pages
- Membership Sites
- MCP
- AI Agents
- Payments
- Sales Automation
---
