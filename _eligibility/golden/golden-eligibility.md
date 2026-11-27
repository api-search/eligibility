---
api_specs:
- filename: golden-entity-api-api-openapi.yml
  format: yaml
  label: Golden Entity API
  slug: golden-entity-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/golden/openapi/golden-entity-api-api-openapi.yml
- filename: golden-query-api-api-openapi.yml
  format: yaml
  label: Golden Query API
  slug: golden-query-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/golden/openapi/golden-query-api-api-openapi.yml
- filename: golden-schema-api-api-openapi.yml
  format: yaml
  label: Golden Schema API
  slug: golden-schema-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/golden/openapi/golden-schema-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are contributing content on behalf of another entity, such as your employer, you should do so from an account separate from your own
    type: business
  minimum_age:
    text: Our Service is not directed at children under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Unauthorized commercial use
    text: you may not use the Service for commercial purposes without our written permission.
  - summary: Reliance on content for critical purposes
    text: Any content available via our Service is not to be relied upon for medical, legal, financial, tax or other critical purposes.
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
name: Golden
provenance_date: '2026-11-09'
provider_name: Golden
provider_slug: golden
slug: golden-eligibility
source_date: '2026-11-09'
source_filename: golden-eligibility.yml
source_heading: Eligibility
source_page: https://golden.com/about/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Golden\naid: golden\nurl: https://golden.com/about/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are contributing content on behalf of another entity, such as your employer, you should do so from\n    an account separate from your own\nrestricted_uses:\n- summary: Unauthorized commercial use\n  text: you may not use the Service for commercial purposes without our written permission.\n- summary: Reliance on content for critical purposes\n  text: Any content available via our Service is not to be relied upon for\
  \ medical, legal, financial, tax or other\n    critical purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you will be asked to provide certain registration details, including your real name and other information.\nminimum_age:\n  value: '13'\n  text: Our Service is not directed at children under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/golden/eligibility/golden-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Golden's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Knowledge Graph
- Company Data
- Data
- Entities
- Artificial Intelligence
- Search
- Business Intelligence
---
