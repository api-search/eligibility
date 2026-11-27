---
api_specs:
- filename: sunrise-atelier-ip-api-openapi.yml
  format: yaml
  label: Sunrise Atelier Ip API
  slug: sunrise-atelier-ip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sunrise-atelier/openapi/sunrise-atelier-ip-api-openapi.yml
- filename: sunrise-atelier-timezone-api-openapi.yml
  format: yaml
  label: Sunrise Atelier Timezone API
  slug: sunrise-atelier-timezone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sunrise-atelier/openapi/sunrise-atelier-timezone-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Permission is granted to temporarily use Sunrise.am for personal, non-commercial transitory viewing only.
    type: individual
  minimum_age:
    text: Our Service is not intended for children under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Commercial use
    text: Use the materials for any commercial purpose or for any public display
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
name: Sunrise Atelier
provenance_date: '2026-11-10'
provider_name: Sunrise Atelier
provider_slug: sunrise-atelier
slug: sunrise-atelier-eligibility
source_date: '2026-11-10'
source_filename: sunrise-atelier-eligibility.yml
source_heading: Eligibility
source_page: https://sunrise.am/info/terms-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sunrise Atelier\naid: sunrise-atelier\nurl: https://sunrise.am/info/terms-privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Permission is granted to temporarily use Sunrise.am for personal, non-commercial transitory viewing only.\nrestricted_uses:\n- summary: Commercial use\n  text: Use the materials for any commercial purpose or for any public display\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our Service is not intended for children under 13 years\
  \ of age.\n"
source_yaml_url: https://artifacts.apis.io/sunrise-atelier/eligibility/sunrise-atelier-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sunrise Atelier's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Time
- Timezone
- Astronomy
- Geolocation
- Sunrise
- Sunset
- Developer API
---
