---
api_specs:
- filename: leia-media-transformation-api-openapi.yml
  format: yaml
  label: Leia Media Transformation API
  slug: leia-media-transformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leia/openapi/leia-media-transformation-api-openapi.yml
- filename: leia-product-pricing-api-openapi.yml
  format: yaml
  label: Leia Product Pricing API
  slug: leia-product-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leia/openapi/leia-product-pricing-api-openapi.yml
- filename: leia-protocol-api-openapi.yml
  format: yaml
  label: Leia Protocol API
  slug: leia-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leia/openapi/leia-protocol-api-openapi.yml
- filename: leia-storage-api-openapi.yml
  format: yaml
  label: Leia Storage API
  slug: leia-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leia/openapi/leia-storage-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Services, you are representing that you are of legal age to enter into a binding contract in your legal jurisdiction
    type: individual
  - text: If you are using the Services on behalf of a business or other entity, you also represent that you have authority to bind them to these Terms.
    type: business
  minimum_age:
    text: You are under 18 years old;
    value: '18'
  restricted_uses:
  - summary: Medical advice
    text: to provide medical advice or medical results interpretation
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
name: Leia
provenance_date: '2026-11-09'
provider_name: Leia
provider_slug: leia
slug: leia-eligibility
source_date: '2026-11-09'
source_filename: leia-eligibility.yml
source_heading: Eligibility
source_page: https://www.leiainc.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leia\naid: leia\nurl: https://www.leiainc.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Services, you are representing that you are of legal age to enter into a binding contract in\n    your legal jurisdiction\n- type: business\n  text: If you are using the Services on behalf of a business or other entity, you also represent that you have\n    authority to bind them to these Terms.\nrestricted_uses:\n- summary: Medical advice\n  text: to provide medical advice or medical results interpretation\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are under 18 years old;\n"
source_yaml_url: https://artifacts.apis.io/leia/eligibility/leia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Leia's own page on 2026-11-09.
synthetic: false
tags:
- 3D
- Spatial Computing
- Computer Vision
- depth-estimation
- Image Processing
- Video Processing
- Generative AI
- Displays
- Media Transformation
- Immersive Experiences
---
