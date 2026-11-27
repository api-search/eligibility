---
api_specs:
- filename: kargo-public-graphql.postman_collection.json
  format: json
  label: Kargo Public GraphQL API
  slug: kargo-public-graphql-api
  spec_type: Postman
  url: https://artifacts.apis.io/kargo-ai/postman/kargo-public-graphql.postman_collection.json
- filename: kargo-ai-documents-api-openapi.yml
  format: yaml
  label: Kargo Documents API
  slug: kargo-ai-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kargo-ai/openapi/kargo-ai-documents-api-openapi.yml
- filename: kargo-ai-sku-master-api-openapi.yml
  format: yaml
  label: Kargo SKU Master API
  slug: kargo-ai-sku-master-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kargo-ai/openapi/kargo-ai-sku-master-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use our Services only if you can form a binding contract with Kargo
    type: individual
  - text: if you are an individual and you access or use our Services on behalf of a company or other entity, such as your employer (together with its affiliates, an “ Organization ”)
    type: business
  minimum_age:
    text: Any use or access to our Services by anyone under 13 (or under 16 in Europe) is strictly prohibited and in violation of these Terms.
    value: '13'
  restricted_uses:
  - summary: Commercial use of personal license
    text: for your personal, noncommercial use only
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
name: Kargo
provenance_date: '2026-11-09'
provider_name: Kargo
provider_slug: kargo-ai
slug: kargo-ai-eligibility
source_date: '2026-11-09'
source_filename: kargo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.kargo.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kargo\naid: kargo-ai\nurl: https://www.kargo.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use our Services only if you can form a binding contract with Kargo\n- type: business\n  text: if you are an individual and you access or use our Services on behalf of a company or other entity, such\n    as your employer (together with its affiliates, an “ Organization ”)\nrestricted_uses:\n- summary: Commercial use of personal license\n  text: for your personal, noncommercial use only\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to our Services by anyone under 13 (or under 16 in Europe) is strictly prohibited and\n    in violation of these Terms.\n"
source_yaml_url: https://artifacts.apis.io/kargo-ai/eligibility/kargo-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kargo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Supply Chain
- Warehouse
- Computer Vision
- Artificial Intelligence
- Shipping
- Inventory
- Industrial Automation
- Freight
- GraphQL
- Webhook
---
