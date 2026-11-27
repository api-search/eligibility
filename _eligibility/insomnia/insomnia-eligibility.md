---
api_specs:
- filename: insomnia-mock-logs-api-openapi.yml
  format: yaml
  label: Insomnia Mock Logs API
  slug: insomnia-mock-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insomnia/openapi/insomnia-mock-logs-api-openapi.yml
- filename: insomnia-mock-routes-api-openapi.yml
  format: yaml
  label: Insomnia Mock Routes API
  slug: insomnia-mock-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insomnia/openapi/insomnia-mock-routes-api-openapi.yml
- filename: insomnia-mock-servers-api-openapi.yml
  format: yaml
  label: Insomnia Mock Servers API
  slug: insomnia-mock-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insomnia/openapi/insomnia-mock-servers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services or Software if you are or are working on behalf of a Specially Designated National (SDN) or a person subject to similar blocking or denied party prohibitions administered by a U.S. government agency.
  entity_types:
  - text: Your agreement to this Agreement also binds your authorized users, your company or organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal activity
    text: You may not use the Services or Software for any illegal activities.
  - summary: Export control and sanctions
    text: You may not use the Services or Software in violation of export control or sanctions laws of the United States or any other applicable jurisdiction.
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
name: Insomnia
provenance_date: '2026-11-09'
provider_name: Insomnia
provider_slug: insomnia
slug: insomnia-eligibility
source_date: '2026-11-09'
source_filename: insomnia-eligibility.yml
source_heading: Eligibility
source_page: https://insomnia.rest/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Insomnia\naid: insomnia\nurl: https://insomnia.rest/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services or Software if you are or are working on behalf of a Specially Designated National\n    (SDN) or a person subject to similar blocking or denied party prohibitions administered by a U.S. government\n    agency.\nentity_types:\n- type: business\n  text: Your agreement to this Agreement also binds your authorized users, your company or organization.\nrestricted_uses:\n- summary: Illegal activity\n  text: You may not use the Services or Software for any\
  \ illegal activities.\n- summary: Export control and sanctions\n  text: You may not use the Services or Software in violation of export control or sanctions laws of the United\n    States or any other applicable jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/insomnia/eligibility/insomnia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Insomnia's own page on 2026-11-09.
synthetic: false
tags:
- API Design
- CLI
- Clients
- Developer Tools
- Mocking
- Platform
- Testing
- OpenAPI
---
