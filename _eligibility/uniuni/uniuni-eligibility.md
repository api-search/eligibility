---
api_specs:
- filename: uniuni-batches-api-openapi.yml
  format: yaml
  label: UniUni Batches API
  slug: uniuni-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-batches-api-openapi.yml
- filename: uniuni-labels-api-openapi.yml
  format: yaml
  label: UniUni Labels API
  slug: uniuni-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-labels-api-openapi.yml
- filename: uniuni-shipments-api-openapi.yml
  format: yaml
  label: UniUni Shipments API
  slug: uniuni-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-shipments-api-openapi.yml
- filename: uniuni-tracking-api-openapi.yml
  format: yaml
  label: UniUni Tracking API
  slug: uniuni-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-tracking-api-openapi.yml
- filename: uniuni-webhooks-api-openapi.yml
  format: yaml
  label: UniUni Webhooks API
  slug: uniuni-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: ship parcels with Uni Express from Uni Express-designed pick-up areas to destinations within Canada designated by you within the Website
  entity_types:
  - text: legally authorized to enter into contractual obligations on behalf of your business
    type: business
  - text: you are at least 18 years old
    type: individual
  minimum_age:
    text: you represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Commercial use only
    text: For commercial use only. This platform is not intended for the shipment and delivery of parcels for personal use or non-commercial purposes.
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
name: UniUni
provenance_date: '2026-11-10'
provider_name: UniUni
provider_slug: uniuni
slug: uniuni-eligibility
source_date: '2026-11-10'
source_filename: uniuni-eligibility.yml
source_heading: Eligibility
source_page: https://help.ship.uniuni.com/en/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UniUni\naid: uniuni\nurl: https://help.ship.uniuni.com/en/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: ship parcels with Uni Express from Uni Express-designed pick-up areas to destinations within Canada designated\n    by you within the Website\nentity_types:\n- type: business\n  text: legally authorized to enter into contractual obligations on behalf of your business\n- type: individual\n  text: you are at least 18 years old\nrestricted_uses:\n- summary: Commercial use only\n  text: For commercial use only. This platform is not intended for the\
  \ shipment and delivery of parcels for personal\n    use or non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/uniuni/eligibility/uniuni-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from UniUni's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Last Mile Delivery
- E-Commerce
- Tracking
- Delivery
---
