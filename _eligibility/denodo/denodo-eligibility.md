---
api_specs:
- filename: rest_api
  format: yaml
  label: Denodo Data Catalog REST API
  slug: data-catalog-api
  spec_type: OpenAPI
  url: https://community.denodo.com/docs/html/browse/9.0/en/vdp/data_catalog/appendix/rest_api/rest_api
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is offered and available to users who are 18 years or older (or the minimum consent age required in your country).
    type: individual
  minimum_age:
    text: The Site is offered and available to users who are 18 years or older (or the minimum consent age required in your country).
    value: '18'
  restricted_uses:
  - summary: Prohibited Site uses
    text: in a way that violates any applicable local, state, national or international law or regulation
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
name: Denodo
provenance_date: '2026-11-09'
provider_name: Denodo
provider_slug: denodo
slug: denodo-eligibility
source_date: '2026-11-09'
source_filename: denodo-eligibility.yml
source_heading: Eligibility
source_page: https://www.denodo.com/en/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Denodo\naid: denodo\nurl: https://www.denodo.com/en/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is offered and available to users who are 18 years or older (or the minimum consent age required\n    in your country).\nrestricted_uses:\n- summary: Prohibited Site uses\n  text: in a way that violates any applicable local, state, national or international law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is offered and\
  \ available to users who are 18 years or older (or the minimum consent age required\n    in your country).\n"
source_yaml_url: https://artifacts.apis.io/denodo/eligibility/denodo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Denodo's own page on 2026-11-09.
synthetic: false
tags:
- Data Catalog
- Data Fabric
- Data Mesh
- Data Virtualization
- GraphQL
- Logical Data Warehouse
- OData
- REST
- Scheduler
- Solution Manager
---
