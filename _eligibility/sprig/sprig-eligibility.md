---
api_specs:
- filename: sprig-purge-api-openapi.yml
  format: yaml
  label: Sprig Purge API
  slug: sprig-purge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprig/openapi/sprig-purge-api-openapi.yml
- filename: sprig-responses-api-openapi.yml
  format: yaml
  label: Sprig Responses API
  slug: sprig-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprig/openapi/sprig-responses-api-openapi.yml
- filename: sprig-surveys-api-openapi.yml
  format: yaml
  label: Sprig Surveys API
  slug: sprig-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprig/openapi/sprig-surveys-api-openapi.yml
- filename: sprig-themes-api-openapi.yml
  format: yaml
  label: Sprig Themes API
  slug: sprig-themes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprig/openapi/sprig-themes-api-openapi.yml
- filename: sprig-users-api-openapi.yml
  format: yaml
  label: Sprig Users API
  slug: sprig-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sprig/openapi/sprig-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: located in (or a national of) a country subject to a U.S. government embargo
  entity_types:
  - text: signed by you or the entity or organization that you represent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High risk activities
    text: will not use the Services for High Risk Activities
  - summary: Sensitive data submission
    text: will not submit Sensitive Data to the Services
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
name: Sprig
provenance_date: '2026-11-10'
provider_name: Sprig
provider_slug: sprig
slug: sprig-eligibility
source_date: '2026-11-10'
source_filename: sprig-eligibility.yml
source_heading: Eligibility
source_page: https://sprig.com/ssa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sprig\naid: sprig\nurl: https://sprig.com/ssa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: located in (or a national of) a country subject to a U.S. government embargo\nentity_types:\n- type: business\n  text: signed by you or the entity or organization that you represent\nrestricted_uses:\n- summary: High risk activities\n  text: will not use the Services for High Risk Activities\n- summary: Sensitive data submission\n  text: will not submit Sensitive Data to the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sprig/eligibility/sprig-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Sprig's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Product Research
- Surveys
- User Insights
- Customer Experience
- Analytics
- Product Analytics
- Artificial Intelligence
- Software-as-a-Service
---
