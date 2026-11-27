---
api_specs:
- filename: rootline-core-openapi-generated.yml
  format: yaml
  label: Rootline core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rootline/openapi/_ae-authored/rootline-core-openapi-generated.yml
- filename: rootline-in-person-payments-openapi-generated.yml
  format: yaml
  label: Rootline in person payments API
  slug: in-person-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rootline/openapi/_ae-authored/rootline-in-person-payments-openapi-generated.yml
- filename: rootline-payments-openapi-generated.yml
  format: yaml
  label: Rootline payments API
  slug: payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rootline/openapi/_ae-authored/rootline-payments-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the identity and background of its direct and indirect shareholders and directors
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Card data storage restriction
    text: it under no circumstance and under no condition may capture, store or transmit in any manner or form any Card Data
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: Rootline reserves the right not to accept Merchant as a user of the Services or to withdraw its acceptance
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rootline
provenance_date: '2026-11-10'
provider_name: Rootline
provider_slug: rootline
slug: rootline-eligibility
source_date: '2026-11-10'
source_filename: rootline-eligibility.yml
source_heading: Eligibility
source_page: https://rootline.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rootline\naid: rootline\nurl: https://rootline.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the identity and background of its direct and indirect shareholders and directors\nrestricted_uses:\n- summary: Card data storage restriction\n  text: it under no circumstance and under no condition may capture, store or transmit in any manner or form any\n    Card Data\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: Rootline reserves the right not to accept Merchant\
  \ as a user of the Services or to withdraw its acceptance\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rootline/eligibility/rootline-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Rootline's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- Embedded Payments
- Platform
---
