---
api_specs:
- filename: mytomorrows-legacy-graphql-proxy-api-openapi.yml
  format: yaml
  label: myTomorrows Legacy GraphQL Proxy API
  slug: mytomorrows-legacy-graphql-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-legacy-graphql-proxy-api-openapi.yml
- filename: mytomorrows-public-api-openapi.yml
  format: yaml
  label: myTomorrows Public API
  slug: mytomorrows-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-public-api-openapi.yml
- filename: mytomorrows-system-api-openapi.yml
  format: yaml
  label: myTomorrows System API
  slug: mytomorrows-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-system-api-openapi.yml
- filename: mytomorrows-anno-api-openapi.yml
  format: yaml
  label: myTomorrows Anno API
  slug: mytomorrows-anno-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-anno-api-openapi.yml
- filename: mytomorrows-autocomplete-api-openapi.yml
  format: yaml
  label: myTomorrows Autocomplete API
  slug: mytomorrows-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-autocomplete-api-openapi.yml
- filename: mytomorrows-docs-api-openapi.yml
  format: yaml
  label: myTomorrows Docs API
  slug: mytomorrows-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-docs-api-openapi.yml
- filename: mytomorrows-document-api-openapi.yml
  format: yaml
  label: myTomorrows Document API
  slug: mytomorrows-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-document-api-openapi.yml
- filename: mytomorrows-es-api-openapi.yml
  format: yaml
  label: myTomorrows Es API
  slug: mytomorrows-es-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-es-api-openapi.yml
- filename: mytomorrows-llm-api-openapi.yml
  format: yaml
  label: myTomorrows Llm API
  slug: mytomorrows-llm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-llm-api-openapi.yml
- filename: mytomorrows-mdt-api-openapi.yml
  format: yaml
  label: myTomorrows Mdt API
  slug: mytomorrows-mdt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-mdt-api-openapi.yml
- filename: mytomorrows-search-api-openapi.yml
  format: yaml
  label: myTomorrows Search API
  slug: mytomorrows-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-search-api-openapi.yml
- filename: mytomorrows-wrapper-api-openapi.yml
  format: yaml
  label: myTomorrows Wrapper API
  slug: mytomorrows-wrapper-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mytomorrows/openapi/mytomorrows-wrapper-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: to pharmacies, hospitals and/or local distributors
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No prohibited military use or sanctioned trade
    text: for any prohibited military use
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: myTomorrows shall not be obliged to accept an order
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: myTomorrows
provenance_date: '2026-11-10'
provider_name: myTomorrows
provider_slug: mytomorrows
slug: mytomorrows-eligibility
source_date: '2026-11-10'
source_filename: mytomorrows-eligibility.yml
source_heading: Eligibility
source_page: https://mytomorrows.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: myTomorrows\naid: mytomorrows\nurl: https://mytomorrows.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: to pharmacies, hospitals and/or local distributors\nrestricted_uses:\n- summary: No prohibited military use or sanctioned trade\n  text: for any prohibited military use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: myTomorrows shall not be obliged to accept an order\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mytomorrows/eligibility/mytomorrows-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from myTomorrows's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Clinical Trials
- Expanded Access
- Pharmaceuticals
- Patient Access
- Life Sciences
- Search
- Artificial Intelligence
---
