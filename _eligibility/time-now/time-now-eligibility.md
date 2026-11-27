---
api_specs:
- filename: time-now-developer-api-openapi.yml
  format: yaml
  label: Time.now Developer API
  slug: time-now-developer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/time-now/openapi/time-now-developer-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Permission is granted to temporarily use time.now for personal, non-commercial purposes for transitory viewing only.
    type: individual
  minimum_age:
    text: Our Service is not directed to children under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Unlawful purposes
    text: For any unlawful purpose or to solicit others to perform unlawful acts
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
name: Time.now
provenance_date: '2026-11-10'
provider_name: Time.now
provider_slug: time-now
slug: time-now-eligibility
source_date: '2026-11-10'
source_filename: time-now-eligibility.yml
source_heading: Eligibility
source_page: https://time.now/info/terms-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Time.now\naid: time-now\nurl: https://time.now/info/terms-privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Permission is granted to temporarily use time.now for personal, non-commercial purposes for transitory viewing\n    only.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: For any unlawful purpose or to solicit others to perform unlawful acts\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our Service is not directed to children under the age\
  \ of 13.\n"
source_yaml_url: https://artifacts.apis.io/time-now/eligibility/time-now-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Time.now's own page on 2026-11-10.
synthetic: false
tags:
- World Time API
- Developer Tools
- IoT
- Web Applications
- Timezone
- Geolocation
---
