---
api_specs:
- filename: aivyro-io-openapi-generated.yml
  format: yaml
  label: Aivyro API
  slug: aivyro-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivyro-io/openapi/_ae-authored/aivyro-io-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The initial offer is intended for businesses.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, fraudulent or abusive uses
    text: Illegal, fraudulent, discriminatory, abusive uses, or uses that violate rights, confidentiality, security, or intellectual property, are prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Aivyro may require confirmation of identity, powers, or special conditions, in proportion to the contract.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aivyro
provenance_date: '2026-11-09'
provider_name: Aivyro
provider_slug: aivyro-io
slug: aivyro-io-eligibility
source_date: '2026-11-09'
source_filename: aivyro-io-eligibility.yml
source_heading: Eligibility
source_page: https://legal.aivyro.io/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aivyro\naid: aivyro-io\nurl: https://legal.aivyro.io/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The initial offer is intended for businesses.\nrestricted_uses:\n- summary: Illegal, fraudulent or abusive uses\n  text: Illegal, fraudulent, discriminatory, abusive uses, or uses that violate rights, confidentiality, security,\n    or intellectual property, are prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Aivyro may require confirmation of identity, powers, or special\
  \ conditions, in proportion to the contract.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aivyro-io/eligibility/aivyro-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Aivyro's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Revenue Engineering
- Platform
- CRM
- Analytics
---
