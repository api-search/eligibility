---
api_specs:
- filename: julep-beauty-cart-api-openapi.yml
  format: yaml
  label: Julep Beauty Cart API
  slug: julep-beauty-cart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/julep-beauty/openapi/julep-beauty-cart-api-openapi.yml
- filename: julep-beauty-discovery-api-openapi.yml
  format: yaml
  label: Julep Beauty Discovery API
  slug: julep-beauty-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/julep-beauty/openapi/julep-beauty-discovery-api-openapi.yml
- filename: julep-beauty-search-api-openapi.yml
  format: yaml
  label: Julep Beauty Search API
  slug: julep-beauty-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/julep-beauty/openapi/julep-beauty-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least 18 years of age or older and are capable of forming a binding contract
    type: individual
  minimum_age:
    text: You must be 18 years old or the age of majority in your jurisdiction of residence to make a purchase on our Website.
    value: '18'
  restricted_uses:
  - summary: No commercial use of website
    text: You may not use this Website for commercial purposes.
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
name: Julep Beauty
provenance_date: '2026-11-09'
provider_name: Julep Beauty
provider_slug: julep-beauty
slug: julep-beauty-eligibility
source_date: '2026-11-09'
source_filename: julep-beauty-eligibility.yml
source_heading: Eligibility
source_page: https://www.julep.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Julep Beauty\naid: julep-beauty\nurl: https://www.julep.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least 18 years of age or older and are capable of forming a binding contract\nrestricted_uses:\n- summary: No commercial use of website\n  text: You may not use this Website for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years old or the age of majority in your\
  \ jurisdiction of residence to make a purchase on\n    our Website.\n"
source_yaml_url: https://artifacts.apis.io/julep-beauty/eligibility/julep-beauty-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Julep Beauty's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beauty
- Cosmetics
- Skincare
- Retail
- E-Commerce
- Direct to Consumer
- Shopify
- Agentic Commerce
- Universal Commerce Protocol
---
