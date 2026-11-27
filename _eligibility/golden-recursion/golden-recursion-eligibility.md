---
api_specs:
- filename: golden-recursion-entity-api-api-openapi.yml
  format: yaml
  label: Golden Recursion Entity API
  slug: golden-recursion-entity-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/golden-recursion/openapi/golden-recursion-entity-api-api-openapi.yml
- filename: golden-recursion-query-api-api-openapi.yml
  format: yaml
  label: Golden Recursion Query API
  slug: golden-recursion-query-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/golden-recursion/openapi/golden-recursion-query-api-api-openapi.yml
- filename: golden-recursion-schema-api-api-openapi.yml
  format: yaml
  label: Golden Recursion Schema API
  slug: golden-recursion-schema-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/golden-recursion/openapi/golden-recursion-schema-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Our Service is not directed at children under the age of 13. If you are younger than 13, your use of our Service violates these Terms and you must stop.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use our Service for any unlawful purpose, including but not limited to committing a criminal offense
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you will be asked to provide certain registration details, including your real name and other information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Golden Recursion
provenance_date: '2026-11-09'
provider_name: Golden Recursion
provider_slug: golden-recursion
slug: golden-recursion-eligibility
source_date: '2026-11-09'
source_filename: golden-recursion-eligibility.yml
source_heading: Eligibility
source_page: https://golden.com/about/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Golden Recursion\naid: golden-recursion\nurl: https://golden.com/about/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use our Service for any unlawful purpose, including but not limited to committing a criminal\n    offense\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you will be asked to provide certain registration details, including your real name and other information.\nminimum_age:\n  value: '13'\n  text: Our Service is not directed\
  \ at children under the age of 13. If you are younger than 13, your use of our\n    Service violates these Terms and you must stop.\n"
source_yaml_url: https://artifacts.apis.io/golden-recursion/eligibility/golden-recursion-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Golden Recursion's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Knowledge Graph
- Data Enrichment
- Entity Data
- Company Data
- Artificial Intelligence
- Semantic Web
- Data
---
