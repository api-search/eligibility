---
api_specs:
- filename: ninoxdb-de-openapi-generated.yml
  format: yaml
  label: Ninox API
  slug: ninoxdb-de-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ninoxdb-de/openapi/_ae-authored/ninoxdb-de-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are a consumer if the purpose of the conclusion of the License Agreement by You cannot be predominantly attributed to your commercial or independent professional activity
    type: individual
  - text: You are an entrepreneur for the purposes of this contract, if You act in the exercise of your commercial or independent professional activity with respect to the conclusion of the License Agreement
    type: business
  minimum_age:
    text: Minimum Age of 18 Years. We do not offer the software to minors.
    value: '18'
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
name: Ninox
provenance_date: '2026-11-10'
provider_name: Ninox
provider_slug: ninoxdb-de
slug: ninoxdb-de-eligibility
source_date: '2026-11-10'
source_filename: ninoxdb-de-eligibility.yml
source_heading: Eligibility
source_page: https://ninox.com/en/legal-notices/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ninox\naid: ninoxdb-de\nurl: https://ninox.com/en/legal-notices/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are a consumer if the purpose of the conclusion of the License Agreement by You cannot be predominantly\n    attributed to your commercial or independent professional activity\n- type: business\n  text: You are an entrepreneur for the purposes of this contract, if You act in the exercise of your commercial\n    or independent professional activity with respect to the conclusion of the License Agreement\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Minimum Age of 18 Years. We do not offer the software to minors.\n"
source_yaml_url: https://artifacts.apis.io/ninoxdb-de/eligibility/ninoxdb-de-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Ninox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Low-Code
- Platform
- Business Apps
- Database
---
