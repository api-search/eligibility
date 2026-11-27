---
api_specs:
- filename: contensis-content-types-api-openapi.yml
  format: yaml
  label: Contensis Content Types API
  slug: contensis-content-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contensis/openapi/contensis-content-types-api-openapi.yml
- filename: contensis-entries-api-openapi.yml
  format: yaml
  label: Contensis Entries API
  slug: contensis-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contensis/openapi/contensis-entries-api-openapi.yml
- filename: contensis-projects-api-openapi.yml
  format: yaml
  label: Contensis Projects API
  slug: contensis-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contensis/openapi/contensis-projects-api-openapi.yml
- filename: contensis-taxonomy-api-openapi.yml
  format: yaml
  label: Contensis Taxonomy API
  slug: contensis-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contensis/openapi/contensis-taxonomy-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You agree to use this site only for lawful purposes.
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
name: Contensis
provenance_date: '2026-11-09'
provider_name: Contensis
provider_slug: contensis
slug: contensis-eligibility
source_date: '2026-11-09'
source_filename: contensis-eligibility.yml
source_heading: Eligibility
source_page: https://www.contensis.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Contensis\naid: contensis\nurl: https://www.contensis.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You agree to use this site only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/contensis/eligibility/contensis-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Contensis's own page on 2026-11-09.
synthetic: false
tags:
- CMS
- Content
- Headless CMS
- Content Management
- Digital Experience Platform
- Content Delivery
- Webhook
- Higher Education
---
