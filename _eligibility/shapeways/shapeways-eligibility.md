---
api_specs:
- filename: shapeways-cart-api-openapi.yml
  format: yaml
  label: Shapeways Cart API
  slug: shapeways-cart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shapeways/openapi/shapeways-cart-api-openapi.yml
- filename: shapeways-materials-api-openapi.yml
  format: yaml
  label: Shapeways Materials API
  slug: shapeways-materials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shapeways/openapi/shapeways-materials-api-openapi.yml
- filename: shapeways-models-api-openapi.yml
  format: yaml
  label: Shapeways Models API
  slug: shapeways-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shapeways/openapi/shapeways-models-api-openapi.yml
- filename: shapeways-orders-api-openapi.yml
  format: yaml
  label: Shapeways Orders API
  slug: shapeways-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shapeways/openapi/shapeways-orders-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Site, apps, products, and services are intended for businesses and their representatives.
    type: business
  - text: We do not cater to individual consumers or those seeking to use our products and services for personal or household purposes.
    type: individual
  minimum_age:
    text: You may not access or use the Site or accept these Terms if you are under 18 years old or not of legal age to enter into a valid contract according to the laws applicable to you.
    value: '18'
  restricted_uses:
  - summary: No export-controlled data
    text: Shapeways does not accept Export Controlled Data, defined as data controlled under E.U. or U.S. law based on your place of order or residency.
  - summary: No weapons in User Content
    text: Your User Content does not contain any weapons or weapon components, including firearms, ammunition, bladed weapons, explosive devices, or accessories;
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
name: Shapeways
provenance_date: '2026-11-10'
provider_name: Shapeways
provider_slug: shapeways
slug: shapeways-eligibility
source_date: '2026-11-10'
source_filename: shapeways-eligibility.yml
source_heading: Eligibility
source_page: https://www.shapeways.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shapeways\naid: shapeways\nurl: https://www.shapeways.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Site, apps, products, and services are intended for businesses and their representatives.\n- type: individual\n  text: We do not cater to individual consumers or those seeking to use our products and services for personal or\n    household purposes.\nrestricted_uses:\n- summary: No export-controlled data\n  text: Shapeways does not accept Export Controlled Data, defined as data controlled under E.U. or U.S.\
  \ law based\n    on your place of order or residency.\n- summary: No weapons in User Content\n  text: Your User Content does not contain any weapons or weapon components, including firearms, ammunition, bladed\n    weapons, explosive devices, or accessories;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the Site or accept these Terms if you are under 18 years old or not of legal age\n    to enter into a valid contract according to the laws applicable to you.\n"
source_yaml_url: https://artifacts.apis.io/shapeways/eligibility/shapeways-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Shapeways's own page on 2026-11-10.
synthetic: false
tags:
- Company
- 3D Printing
- Manufacturing
- Prototyping
- Hardware
- Fulfillment
- E-Commerce
---
