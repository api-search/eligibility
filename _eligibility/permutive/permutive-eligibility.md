---
api_specs:
- filename: permutive-contextual-api-openapi.yml
  format: yaml
  label: Permutive Contextual API
  slug: permutive-contextual-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-contextual-api-openapi.yml
- filename: permutive-cohorts-api-openapi.yml
  format: yaml
  label: Permutive Cohorts API
  slug: permutive-cohorts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-cohorts-api-openapi.yml
- filename: permutive-events-api-openapi.yml
  format: yaml
  label: Permutive Events API
  slug: permutive-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-events-api-openapi.yml
- filename: permutive-identity-api-openapi.yml
  format: yaml
  label: Permutive Identity API
  slug: permutive-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-identity-api-openapi.yml
- filename: permutive-segmentation-api-openapi.yml
  format: yaml
  label: Permutive Segmentation API
  slug: permutive-segmentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-segmentation-api-openapi.yml
- filename: permutive-taxonomy-api-openapi.yml
  format: yaml
  label: Permutive Taxonomy API
  slug: permutive-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-taxonomy-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We only provide our Site for private use. You agree not to use our Site for any commercial or business purposes
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial or business use of the Site
    text: You agree not to use our Site for any commercial or business purposes
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
name: Permutive
provenance_date: '2026-11-10'
provider_name: Permutive
provider_slug: permutive
slug: permutive-eligibility
source_date: '2026-11-10'
source_filename: permutive-eligibility.yml
source_heading: Eligibility
source_page: https://permutive.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Permutive\naid: permutive\nurl: https://permutive.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We only provide our Site for private use. You agree not to use our Site for any commercial or business purposes\nrestricted_uses:\n- summary: No commercial or business use of the Site\n  text: You agree not to use our Site for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/permutive/eligibility/permutive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Permutive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Publishing
- Advertising
- AdTech
- MarTech
- Audiences
- Data Collaboration
- Data Management Platform
- Contextual
- Identity
- Segmentation
- Agents
- A2A
---
