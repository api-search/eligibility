---
api_specs:
- filename: remem-me-access-api-openapi.yml
  format: yaml
  label: remem-me Access API
  slug: remem-me-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/remem-me/openapi/remem-me-access-api-openapi.yml
- filename: remem-me-collections-api-openapi.yml
  format: yaml
  label: remem-me Collections API
  slug: remem-me-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/remem-me/openapi/remem-me-collections-api-openapi.yml
- filename: remem-me-replication-api-openapi.yml
  format: yaml
  label: remem-me Replication API
  slug: remem-me-replication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/remem-me/openapi/remem-me-replication-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a minor, you need the permission of a parent or guardian to register.
    type: individual
  minimum_age:
    text: If you are a minor, you need the permission of a parent or guardian to register.
    value: null
  restricted_uses:
  - summary: Prohibited content types
    text: Publish content that is hateful, discriminatory, pornographic or misleading, or that glorifies violence
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
name: remem-me
provenance_date: '2026-11-10'
provider_name: remem-me
provider_slug: remem-me
slug: remem-me-eligibility
source_date: '2026-11-10'
source_filename: remem-me-eligibility.yml
source_heading: Eligibility
source_page: https://www.remem.me/docs/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: remem-me\naid: remem-me\nurl: https://www.remem.me/docs/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a minor, you need the permission of a parent or guardian to register.\nrestricted_uses:\n- summary: Prohibited content types\n  text: Publish content that is hateful, discriminatory, pornographic or misleading, or that glorifies violence\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you are a minor, you need the permission of a parent or\
  \ guardian to register.\n"
source_yaml_url: https://artifacts.apis.io/remem-me/eligibility/remem-me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from remem-me's own page on 2026-11-10.
synthetic: false
tags:
- Bible
- Memory
- Non-Profit
- Education
- Mobile App
- Open Source
---
