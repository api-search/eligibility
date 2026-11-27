---
api_specs:
- filename: arcnautical-com-account-api-openapi.yml
  format: yaml
  label: ArcNautical Account API
  slug: arcnautical-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-account-api-openapi.yml
- filename: arcnautical-com-cargo-screening-api-openapi.yml
  format: yaml
  label: ArcNautical Cargo screening API
  slug: arcnautical-com-cargo-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-cargo-screening-api-openapi.yml
- filename: arcnautical-com-corridor-monitors-api-openapi.yml
  format: yaml
  label: ArcNautical Corridor monitors API
  slug: arcnautical-com-corridor-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-corridor-monitors-api-openapi.yml
- filename: arcnautical-com-crew-placement-api-openapi.yml
  format: yaml
  label: ArcNautical Crew placement API
  slug: arcnautical-com-crew-placement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-crew-placement-api-openapi.yml
- filename: arcnautical-com-exports-api-openapi.yml
  format: yaml
  label: ArcNautical Exports API
  slug: arcnautical-com-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-exports-api-openapi.yml
- filename: arcnautical-com-fleets-api-openapi.yml
  format: yaml
  label: ArcNautical Fleets API
  slug: arcnautical-com-fleets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-fleets-api-openapi.yml
- filename: arcnautical-com-port-lookup-api-openapi.yml
  format: yaml
  label: ArcNautical Port lookup API
  slug: arcnautical-com-port-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-port-lookup-api-openapi.yml
- filename: arcnautical-com-public-vessel-check-api-openapi.yml
  format: yaml
  label: ArcNautical Public vessel check API
  slug: arcnautical-com-public-vessel-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-public-vessel-check-api-openapi.yml
- filename: arcnautical-com-vessel-monitors-api-openapi.yml
  format: yaml
  label: ArcNautical Vessel monitors API
  slug: arcnautical-com-vessel-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-vessel-monitors-api-openapi.yml
- filename: arcnautical-com-vessel-screening-api-openapi.yml
  format: yaml
  label: ArcNautical Vessel screening API
  slug: arcnautical-com-vessel-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-vessel-screening-api-openapi.yml
- filename: arcnautical-com-voyage-assessments-api-openapi.yml
  format: yaml
  label: ArcNautical Voyage assessments API
  slug: arcnautical-com-voyage-assessments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-voyage-assessments-api-openapi.yml
- filename: arcnautical-com-webhooks-api-openapi.yml
  format: yaml
  label: ArcNautical Webhooks API
  slug: arcnautical-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per individual or organization. Multiple accounts for the same entity may be terminated.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions evasion
    text: Use the Service to facilitate or enable sanctions evasion
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address and create a secure password to register.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ArcNautical
provenance_date: '2026-11-09'
provider_name: ArcNautical
provider_slug: arcnautical-com
slug: arcnautical-com-eligibility
source_date: '2026-11-09'
source_filename: arcnautical-com-eligibility.yml
source_heading: Eligibility
source_page: https://arcnautical.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ArcNautical\naid: arcnautical-com\nurl: https://arcnautical.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: One account per individual or organization. Multiple accounts for the same entity may be terminated.\nrestricted_uses:\n- summary: Sanctions evasion\n  text: Use the Service to facilitate or enable sanctions evasion\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address and create a secure password to register.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arcnautical-com/eligibility/arcnautical-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ArcNautical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Maritime
- Compliance
- Data
- Screening
---
