---
api_specs:
- filename: ayhire-com-account-api-openapi.yml
  format: yaml
  label: ayhire-com Account API
  slug: ayhire-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-account-api-openapi.yml
- filename: ayhire-com-company-maps-api-openapi.yml
  format: yaml
  label: ayhire-com Company maps API
  slug: ayhire-com-company-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-company-maps-api-openapi.yml
- filename: ayhire-com-integrations-api-openapi.yml
  format: yaml
  label: ayhire-com Integrations API
  slug: ayhire-com-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-integrations-api-openapi.yml
- filename: ayhire-com-people-api-openapi.yml
  format: yaml
  label: ayhire-com People API
  slug: ayhire-com-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-people-api-openapi.yml
- filename: ayhire-com-research-api-openapi.yml
  format: yaml
  label: ayhire-com Research API
  slug: ayhire-com-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-research-api-openapi.yml
- filename: ayhire-com-roles-api-openapi.yml
  format: yaml
  label: ayhire-com Roles API
  slug: ayhire-com-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-roles-api-openapi.yml
- filename: ayhire-com-watching-api-openapi.yml
  format: yaml
  label: ayhire-com Watching API
  slug: ayhire-com-watching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-watching-api-openapi.yml
- filename: ayhire-com-workspaces-api-openapi.yml
  format: yaml
  label: ayhire-com Workspaces API
  slug: ayhire-com-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-workspaces-api-openapi.yml
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
  - summary: Harassment or unfair treatment
    text: use AyHire to harass anyone, or to treat people unfairly because of who they are rather than what they have built
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
name: ayhire-com
provenance_date: '2026-11-09'
provider_name: ayhire-com
provider_slug: ayhire-com
slug: ayhire-com-eligibility
source_date: '2026-11-09'
source_filename: ayhire-com-eligibility.yml
source_heading: Eligibility
source_page: https://ayhire.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ayhire-com\naid: ayhire-com\nurl: https://ayhire.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment or unfair treatment\n  text: use AyHire to harass anyone, or to treat people unfairly because of who they are rather than what they have\n    built\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ayhire-com/eligibility/ayhire-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ayhire-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hiring
- Developer Tools
- Recruiting
- Open Source
---
