---
api_specs:
- filename: tessie-driver-management-api-openapi.yml
  format: yaml
  label: Tessie Driver Management API
  slug: tessie-driver-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessie/openapi/tessie-driver-management-api-openapi.yml
- filename: tessie-telemetry-configuration-api-openapi.yml
  format: yaml
  label: Tessie Telemetry Configuration API
  slug: tessie-telemetry-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessie/openapi/tessie-telemetry-configuration-api-openapi.yml
- filename: tessie-vehicle-commands-api-openapi.yml
  format: yaml
  label: Tessie Vehicle Commands API
  slug: tessie-vehicle-commands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessie/openapi/tessie-vehicle-commands-api-openapi.yml
- filename: tessie-vehicle-data-api-openapi.yml
  format: yaml
  label: Tessie Vehicle Data API
  slug: tessie-vehicle-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessie/openapi/tessie-vehicle-data-api-openapi.yml
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
  - summary: Prohibited content
    text: use, display or distribution of Tessie together with material that is pornographic, racist, vulgar, obscene, defamatory, libelous, abusive, promoting hatred, discriminating or displaying prejudice based on religion, ethnic heritage, race, sexual orientation or age is strictly prohibited.
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
name: Tessie
provenance_date: '2026-11-10'
provider_name: Tessie
provider_slug: tessie
slug: tessie-eligibility
source_date: '2026-11-10'
source_filename: tessie-eligibility.yml
source_heading: Eligibility
source_page: https://www.tessie.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tessie\naid: tessie\nurl: https://www.tessie.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content\n  text: use, display or distribution of Tessie together with material that is pornographic, racist, vulgar, obscene,\n    defamatory, libelous, abusive, promoting hatred, discriminating or displaying prejudice based on religion, ethnic\n    heritage, race, sexual orientation or age is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tessie/eligibility/tessie-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Tessie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tesla
- Fleet Management
- Automotive
---
