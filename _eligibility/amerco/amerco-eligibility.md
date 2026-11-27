---
api_specs:
- filename: amerco-wssapi-api-openapi.yml
  format: yaml
  label: AMERCO Wss API
  slug: amerco-wssapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amerco/openapi/amerco-wssapi-api-openapi.yml
- filename: amerco-wssapiv4-api-openapi.yml
  format: yaml
  label: AMERCO Wss API V4 API
  slug: amerco-wssapiv4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amerco/openapi/amerco-wssapiv4-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Information on this Website includes descriptions of products and services available in the United States of America and Canada and is not intended for use in other locations.
  entity_types:
  - text: If you are registering a U-Haul Account for a business, organization or other legal entity, you represent and warrant that you have the authority to legally bind that entity
    type: business
  - text: You must be at least 13 years of age to use this Website.
    type: individual
  minimum_age:
    text: You must be at least 13 years of age to use this Website.
    value: '13'
  restricted_uses:
  - summary: Export restrictions
    text: You may not use or export the materials in this Website in violation of U.S. export laws and regulations.
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
name: AMERCO
provenance_date: '2026-11-09'
provider_name: AMERCO
provider_slug: amerco
slug: amerco-eligibility
source_date: '2026-11-09'
source_filename: amerco-eligibility.yml
source_heading: Eligibility
source_page: https://www.uhaul.com/Legal/TermsOfUse/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AMERCO\naid: amerco\nurl: https://www.uhaul.com/Legal/TermsOfUse/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Information on this Website includes descriptions of products and services available in the United States\n    of America and Canada and is not intended for use in other locations.\nentity_types:\n- type: business\n  text: If you are registering a U-Haul Account for a business, organization or other legal entity, you represent\n    and warrant that you have the authority to legally bind that entity\n- type: individual\n  text: You must be at least 13 years\
  \ of age to use this Website.\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not use or export the materials in this Website in violation of U.S. export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use this Website.\n"
source_yaml_url: https://artifacts.apis.io/amerco/eligibility/amerco-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AMERCO's own page on 2026-11-09.
synthetic: false
tags:
- Moving
- Storage
- Truck Rental
- Logistics
- Consumer Services
- Fortune 1000
- Self Storage
---
