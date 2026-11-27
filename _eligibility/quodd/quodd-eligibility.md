---
api_specs:
- filename: quodd-snapshots-api-openapi.yml
  format: yaml
  label: QUODD Snap API
  slug: quodd-snap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quodd/openapi/quodd-snapshots-api-openapi.yml
- filename: quodd-snapshots-api-openapi.yml
  format: yaml
  label: QUODD Batch Snaps API
  slug: quodd-batch-snaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quodd/openapi/quodd-snapshots-api-openapi.yml
- filename: quodd-options-api-openapi.yml
  format: yaml
  label: QUODD Options Snaps API
  slug: quodd-options-snaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quodd/openapi/quodd-options-api-openapi.yml
- filename: quodd-authentication-api-openapi.yml
  format: yaml
  label: QUODD Authentication Token API
  slug: quodd-authentication-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quodd/openapi/quodd-authentication-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept or agree to this Agreement on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-employee redistribution restricted
    text: Customer may not display or make the Data or Third Party Data available in any Data Exchange Format to non-employee users, including but not limited to, vendors, contractors, partners and the general public
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
name: QUODD
provenance_date: '2026-11-10'
provider_name: QUODD
provider_slug: quodd
slug: quodd-eligibility
source_date: '2026-11-10'
source_filename: quodd-eligibility.yml
source_heading: Eligibility
source_page: https://www.quodd.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QUODD\naid: quodd\nurl: https://www.quodd.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept or agree to this Agreement on behalf of a company or other legal entity, you represent and\n    warrant that you have the authority to bind that company or other legal entity to this Agreement\nrestricted_uses:\n- summary: Non-employee redistribution restricted\n  text: Customer may not display or make the Data or Third Party Data available in any Data Exchange Format to non-employee\n    users, including but not limited\
  \ to, vendors, contractors, partners and the general public\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quodd/eligibility/quodd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from QUODD's own page on 2026-11-10.
synthetic: false
tags:
- Market Data
- Real-Time Data
- Financial Data
- Streaming
- Historical Data
- Reference Data
- Quotes
- Fintech
---
