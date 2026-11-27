---
api_specs:
- filename: fulcrum-audio-api-openapi.yml
  format: yaml
  label: Fulcrum Audio API
  slug: fulcrum-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-audio-api-openapi.yml
- filename: fulcrum-changesets-api-openapi.yml
  format: yaml
  label: Fulcrum Changesets API
  slug: fulcrum-changesets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-changesets-api-openapi.yml
- filename: fulcrum-choice-lists-api-openapi.yml
  format: yaml
  label: Fulcrum Choice Lists API
  slug: fulcrum-choice-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-choice-lists-api-openapi.yml
- filename: fulcrum-classification-sets-api-openapi.yml
  format: yaml
  label: Fulcrum Classification Sets API
  slug: fulcrum-classification-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-classification-sets-api-openapi.yml
- filename: fulcrum-forms-api-openapi.yml
  format: yaml
  label: Fulcrum Forms API
  slug: fulcrum-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-forms-api-openapi.yml
- filename: fulcrum-layers-api-openapi.yml
  format: yaml
  label: Fulcrum Layers API
  slug: fulcrum-layers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-layers-api-openapi.yml
- filename: fulcrum-memberships-api-openapi.yml
  format: yaml
  label: Fulcrum Memberships API
  slug: fulcrum-memberships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-memberships-api-openapi.yml
- filename: fulcrum-photos-api-openapi.yml
  format: yaml
  label: Fulcrum Photos API
  slug: fulcrum-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-photos-api-openapi.yml
- filename: fulcrum-projects-api-openapi.yml
  format: yaml
  label: Fulcrum Projects API
  slug: fulcrum-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-projects-api-openapi.yml
- filename: fulcrum-query-api-openapi.yml
  format: yaml
  label: Fulcrum Query API
  slug: fulcrum-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-query-api-openapi.yml
- filename: fulcrum-records-api-openapi.yml
  format: yaml
  label: Fulcrum Records API
  slug: fulcrum-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-records-api-openapi.yml
- filename: fulcrum-roles-api-openapi.yml
  format: yaml
  label: Fulcrum Roles API
  slug: fulcrum-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-roles-api-openapi.yml
- filename: fulcrum-signatures-api-openapi.yml
  format: yaml
  label: Fulcrum Signatures API
  slug: fulcrum-signatures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-signatures-api-openapi.yml
- filename: fulcrum-videos-api-openapi.yml
  format: yaml
  label: Fulcrum Videos API
  slug: fulcrum-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-videos-api-openapi.yml
- filename: fulcrum-webhooks-api-openapi.yml
  format: yaml
  label: Fulcrum Webhooks API
  slug: fulcrum-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - RU
    - BY
    served: []
    text: Customer represents it is not located, ordinarily resident, or organized in a Sanctioned Jurisdiction (including Cuba, Iran, North Korea, and the regions of Ukraine occupied by Russia); transfers to the Russian Federation, Belarus, or any Sanctioned Jurisdiction are restricted unless authorized by SNI.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive information and minors
    text: use Fulcrum to collect information about or from any minor.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fulcrum
provenance_date: '2026-11-09'
provider_name: Fulcrum
provider_slug: fulcrum
slug: fulcrum-eligibility
source_date: '2026-11-09'
source_filename: fulcrum-eligibility.yml
source_heading: Eligibility
source_page: https://www.fulcrumapp.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fulcrum\naid: fulcrum\nurl: https://www.fulcrumapp.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - RU\n  - BY\n  text: Customer represents it is not located, ordinarily resident, or organized in a Sanctioned Jurisdiction (including\n    Cuba, Iran, North Korea, and the regions of Ukraine occupied by Russia); transfers to the Russian Federation,\n    Belarus, or any Sanctioned Jurisdiction are restricted unless authorized by SNI.\nentity_types: []\nrestricted_uses:\n- summary: Sensitive information and minors\n  text: use Fulcrum\
  \ to collect information about or from any minor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fulcrum/eligibility/fulcrum-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Fulcrum's own page on 2026-11-09.
synthetic: false
tags:
- Data Collection
- Field Data
- Geospatial
- Process Management
- Mobile
---
