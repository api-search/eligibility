---
api_specs:
- filename: andel-purchases-api-openapi.yml
  format: yaml
  label: Andel Purchases API
  slug: andel-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/andel/openapi/andel-purchases-api-openapi.yml
- filename: andel-webhooks-api-openapi.yml
  format: yaml
  label: Andel Webhooks API
  slug: andel-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/andel/openapi/andel-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Service for use only by persons located in the United States
  entity_types:
  - text: you are permitted to use the Service solely for your own personal, non-commercial use.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the right to bind such organization to this Agreement
    type: business
  minimum_age:
    text: You must be at least 18 years of age to become a Member.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: solely for your own personal, non-commercial use
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
name: Andel
provenance_date: '2026-11-09'
provider_name: Andel
provider_slug: andel
slug: andel-eligibility
source_date: '2026-11-09'
source_filename: andel-eligibility.yml
source_heading: Eligibility
source_page: https://www.andel.org/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Andel\naid: andel\nurl: https://www.andel.org/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Service for use only by persons located in the United States\nentity_types:\n- type: individual\n  text: you are permitted to use the Service solely for your own personal, non-commercial use.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the right to bind\n    such organization to this Agreement\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text:\
  \ solely for your own personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to become a Member.\n"
source_yaml_url: https://artifacts.apis.io/andel/eligibility/andel-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Andel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Pharmacy Benefits
- Drug Pricing
- Specialty Medications
- Data Exchange
- Webhook
---
