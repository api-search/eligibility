---
api_specs:
- filename: hypixel-housing-api-openapi.yml
  format: yaml
  label: Hypixel Housing API
  slug: hypixel-housing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypixel/openapi/hypixel-housing-api-openapi.yml
- filename: hypixel-other-api-openapi.yml
  format: yaml
  label: Hypixel Other API
  slug: hypixel-other-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypixel/openapi/hypixel-other-api-openapi.yml
- filename: hypixel-player-data-api-openapi.yml
  format: yaml
  label: Hypixel Player Data API
  slug: hypixel-player-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypixel/openapi/hypixel-player-data-api-openapi.yml
- filename: hypixel-resources-api-openapi.yml
  format: yaml
  label: Hypixel Resources API
  slug: hypixel-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypixel/openapi/hypixel-resources-api-openapi.yml
- filename: hypixel-skyblock-api-openapi.yml
  format: yaml
  label: Hypixel SkyBlock API
  slug: hypixel-skyblock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypixel/openapi/hypixel-skyblock-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Hypixel may not offer the Services in all countries or geographic locations; and You are solely responsible for any internet connection and mobile fees that you may incur as a result of using our Services.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial exploitation of the Services
    text: Lease, sell, rent, or otherwise exploit for commercial purposes any part of the Services, including without limitation access to or use of the Services;
  - summary: Use where prohibited by law
    text: Use the Services where it is prohibited by law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you have been previously banned from using any Hypixel Services, you may not use our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hypixel
provenance_date: '2026-11-09'
provider_name: Hypixel
provider_slug: hypixel
slug: hypixel-eligibility
source_date: '2026-11-09'
source_filename: hypixel-eligibility.yml
source_heading: Eligibility
source_page: https://hypixel.net/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hypixel\naid: hypixel\nurl: https://hypixel.net/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Hypixel may not offer the Services in all countries or geographic locations; and You are solely responsible\n    for any internet connection and mobile fees that you may incur as a result of using our Services.\nentity_types: []\nrestricted_uses:\n- summary: Commercial exploitation of the Services\n  text: Lease, sell, rent, or otherwise exploit for commercial purposes any part of the Services, including without\n    limitation access to or use of the Services;\n- summary: Use where\
  \ prohibited by law\n  text: Use the Services where it is prohibited by law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you have been previously banned from using any Hypixel Services, you may not use our Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hypixel/eligibility/hypixel-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Hypixel's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Minecraft
- Player Stats
- Leaderboards
- SkyBlock
- Public APIs
- Video Games
---
