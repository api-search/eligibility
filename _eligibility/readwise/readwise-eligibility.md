---
api_specs:
- filename: readwise-openapi-generated.yml
  format: yaml
  label: Readwise API
  slug: readwise-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/readwise/openapi/_ae-authored/readwise-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You may use the Service only if you: are at least 16 years old; have permission from a parent or legal guardian, if you are under 18 or under the age of majority where you live'
    type: individual
  minimum_age:
    text: are at least 16 years old
    value: '16'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: are not barred from using the Service or buying content under applicable export or sanctions laws
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
name: Readwise
provenance_date: '2026-11-10'
provider_name: Readwise
provider_slug: readwise
slug: readwise-eligibility
source_date: '2026-11-10'
source_filename: readwise-eligibility.yml
source_heading: Eligibility
source_page: https://readwise.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Readwise\naid: readwise\nurl: https://readwise.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You may use the Service only if you: are at least 16 years old; have permission from a parent or legal\n    guardian, if you are under 18 or under the age of majority where you live'\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: are not barred from using the Service or buying content under applicable export or sanctions laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '16'\n  text: are at least 16 years old\n"
source_yaml_url: https://artifacts.apis.io/readwise/eligibility/readwise-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Readwise's own page on 2026-11-10.
synthetic: false
tags:
- Reading
- Productivity
- Knowledge Management
- Software-as-a-Service
---
