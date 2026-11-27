---
api_specs:
- filename: canopypay-io-openapi-generated.yml
  format: yaml
  label: canopypay-io API
  slug: canopypay-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopypay-io/openapi/_ae-authored/canopypay-io-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A business integrates Canopy and creates a payment intent for one of its users.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or sanctioned activity
    text: You must not use Canopy for unlawful activity, to evade sanctions, or to move funds you are not entitled to move.
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
name: canopypay-io
provenance_date: '2026-11-09'
provider_name: canopypay-io
provider_slug: canopypay-io
slug: canopypay-io-eligibility
source_date: '2026-11-09'
source_filename: canopypay-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.canopypay.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: canopypay-io\naid: canopypay-io\nurl: https://www.canopypay.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: A business integrates Canopy and creates a payment intent for one of its users.\nrestricted_uses:\n- summary: Unlawful or sanctioned activity\n  text: You must not use Canopy for unlawful activity, to evade sanctions, or to move funds you are not entitled\n    to move.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/canopypay-io/eligibility/canopypay-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from canopypay-io's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Cryptocurrency
- Payments
- Deposit
---
