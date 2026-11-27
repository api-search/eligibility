---
api_specs:
- filename: orvel-dev-e-invoicing-api-openapi.yml
  format: yaml
  label: orvel-dev E Invoicing API
  slug: orvel-dev-e-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orvel-dev/openapi/orvel-dev-e-invoicing-api-openapi.yml
- filename: orvel-dev-verification-api-openapi.yml
  format: yaml
  label: orvel-dev Verification API
  slug: orvel-dev-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orvel-dev/openapi/orvel-dev-verification-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: by any business customer (“the Customer”). The service is for professional use and is not intended for consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Authorised websites only
    text: The Customer warrants that it operates the registered website or is authorised to have it audited.
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
name: orvel-dev
provenance_date: '2026-11-10'
provider_name: orvel-dev
provider_slug: orvel-dev
slug: orvel-dev-eligibility
source_date: '2026-11-10'
source_filename: orvel-dev-eligibility.yml
source_heading: Eligibility
source_page: https://access.orvel.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: orvel-dev\naid: orvel-dev\nurl: https://access.orvel.dev/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: by any business customer (“the Customer”). The service is for professional use and is not intended for consumers.\nrestricted_uses:\n- summary: Authorised websites only\n  text: The Customer warrants that it operates the registered website or is authorised to have it audited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/orvel-dev/eligibility/orvel-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from orvel-dev's own page on 2026-11-10.
synthetic: false
tags:
- E-Invoicing
- Accessibility
- France
- EU
---
