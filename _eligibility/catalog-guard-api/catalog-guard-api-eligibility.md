---
api_specs:
- filename: catalog-guard-api-catalog-api-openapi.yml
  format: yaml
  label: Catalog Guard API Catalog API
  slug: catalog-guard-api-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catalog-guard-api/openapi/catalog-guard-api-catalog-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Catalog Guard may evaluate voluntary requests from legitimate net-new merchants
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No existing-store requests
    text: Existing stores are not accepted through this request path.
  - summary: No guaranteed outcomes
    text: No outcome, approval, launch, sales, or availability is guaranteed.
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
name: Catalog Guard API
provenance_date: '2026-11-09'
provider_name: Catalog Guard API
provider_slug: catalog-guard-api
slug: catalog-guard-api-eligibility
source_date: '2026-11-09'
source_filename: catalog-guard-api-eligibility.yml
source_heading: Eligibility
source_page: https://catalogguard.noahcortezj-c.workers.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Catalog Guard API\naid: catalog-guard-api\nurl: https://catalogguard.noahcortezj-c.workers.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Catalog Guard may evaluate voluntary requests from legitimate net-new merchants\nrestricted_uses:\n- summary: No existing-store requests\n  text: Existing stores are not accepted through this request path.\n- summary: No guaranteed outcomes\n  text: No outcome, approval, launch, sales, or availability is guaranteed.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/catalog-guard-api/eligibility/catalog-guard-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Catalog Guard API's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- catalog-validation
- Shopify
- Data Quality
- CSV validation
- product-data-qa
- data-preflight
- Data Validation
- Retail
---
