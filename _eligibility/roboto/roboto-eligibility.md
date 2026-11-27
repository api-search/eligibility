---
api_specs:
- filename: roboto-discovery-api-openapi.yml
  format: yaml
  label: Roboto Discovery API
  slug: roboto-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roboto/openapi/roboto-discovery-api-openapi.yml
- filename: roboto-markdown-api-openapi.yml
  format: yaml
  label: Roboto Markdown API
  slug: roboto-markdown-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roboto/openapi/roboto-markdown-api-openapi.yml
- filename: roboto-navigation-api-openapi.yml
  format: yaml
  label: Roboto Navigation API
  slug: roboto-navigation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roboto/openapi/roboto-navigation-api-openapi.yml
- filename: roboto-pages-api-openapi.yml
  format: yaml
  label: Roboto Pages API
  slug: roboto-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roboto/openapi/roboto-pages-api-openapi.yml
- filename: roboto-search-api-openapi.yml
  format: yaml
  label: Roboto Search API
  slug: roboto-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roboto/openapi/roboto-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are entering into this agreement on behalf of an organization or entity, references to "customer" and "you" in this agreement, except this sentence, refer to that organization or entity
    type: business
  - text: These are intended for users who are at least 18 years old.
    type: individual
  minimum_age:
    text: These are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Personal Data storage at customer risk
    text: Customer’s storage of any Personal Data in connection with its use of the Services is at Customer’s own risk, and Roboto will bear no risk or liability for the same.
  - summary: Export control compliance
    text: Customer hereby certifies that Customer will comply with all current US Export Control laws.
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
name: Roboto
provenance_date: '2026-11-10'
provider_name: Roboto
provider_slug: roboto
slug: roboto-eligibility
source_date: '2026-11-10'
source_filename: roboto-eligibility.yml
source_heading: Eligibility
source_page: https://www.roboto.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roboto\naid: roboto\nurl: https://www.roboto.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are entering into this agreement on behalf of an organization or entity, references to \"customer\"\n    and \"you\" in this agreement, except this sentence, refer to that organization or entity\n- type: individual\n  text: These are intended for users who are at least 18 years old.\nrestricted_uses:\n- summary: Personal Data storage at customer risk\n  text: Customer’s storage of any Personal Data in connection with its use\
  \ of the Services is at Customer’s own\n    risk, and Roboto will bear no risk or liability for the same.\n- summary: Export control compliance\n  text: Customer hereby certifies that Customer will comply with all current US Export Control laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: These are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/roboto/eligibility/roboto-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Roboto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Artificial Intelligence
- Analytics
- Platform
---
