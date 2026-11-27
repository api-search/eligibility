---
api_specs:
- filename: gadget-actions-openapi-generated.yml
  format: yaml
  label: Gadget actions API
  slug: actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gadget/openapi/_ae-authored/gadget-actions-openapi-generated.yml
- filename: gadget-core-openapi-generated.yml
  format: yaml
  label: Gadget core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gadget/openapi/_ae-authored/gadget-core-openapi-generated.yml
- filename: gadget-http-routes-openapi-generated.yml
  format: yaml
  label: Gadget http routes API
  slug: http-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gadget/openapi/_ae-authored/gadget-http-routes-openapi-generated.yml
- filename: gadget-plugins-openapi-generated.yml
  format: yaml
  label: Gadget plugins API
  slug: plugins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gadget/openapi/_ae-authored/gadget-plugins-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE AGREEING TO OUR USER AGREEMENT ON BEHALF OF AN ENTITY OR ORGANIZATION, YOU HEREBY REPRESENT AND WARRANT THAT YOU HAVE ALL THE NECESSARY PERMISSIONS AND AUTHORITY TO AGREE AND TO BIND SUCH ENTITY.
    type: business
  minimum_age:
    text: You must be at least of the age of majority in your jurisdiction to use the Services.
    value: age of majority
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Content that would constitute, encourage or provide instructions for a criminal offense
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
name: Gadget
provenance_date: '2026-11-09'
provider_name: Gadget
provider_slug: gadget
slug: gadget-eligibility
source_date: '2026-11-09'
source_filename: gadget-eligibility.yml
source_heading: Eligibility
source_page: https://gadget.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gadget\naid: gadget\nurl: https://gadget.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE AGREEING TO OUR USER AGREEMENT ON BEHALF OF AN ENTITY OR ORGANIZATION, YOU HEREBY REPRESENT AND\n    WARRANT THAT YOU HAVE ALL THE NECESSARY PERMISSIONS AND AUTHORITY TO AGREE AND TO BIND SUCH ENTITY.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Content that would constitute, encourage or provide instructions for a criminal offense\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: age of majority\n  text: You must be at least of the age of majority in your jurisdiction to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/gadget/eligibility/gadget-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Gadget's own page on 2026-11-09.
synthetic: false
tags:
- Platform
- Software-as-a-Service
- Development
- Full-Stack
---
