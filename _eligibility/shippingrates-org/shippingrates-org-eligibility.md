---
api_specs:
- filename: shippingrates-org-openapi-generated.yml
  format: yaml
  label: shippingrates-org API
  slug: shippingrates-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippingrates-org/openapi/_ae-authored/shippingrates-org-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are acting on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
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
name: shippingrates-org
provenance_date: '2026-11-10'
provider_name: shippingrates-org
provider_slug: shippingrates-org
slug: shippingrates-org-eligibility
source_date: '2026-11-10'
source_filename: shippingrates-org-eligibility.yml
source_heading: Eligibility
source_page: https://shippingrates.org/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: shippingrates-org\naid: shippingrates-org\nurl: https://shippingrates.org/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are acting on behalf of an organization, you represent that you have authority to bind that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shippingrates-org/eligibility/shippingrates-org-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from shippingrates-org's own page on 2026-11-10.
synthetic: false
tags:
- Shipping
- Freight
- Logistics
- Rates
---
