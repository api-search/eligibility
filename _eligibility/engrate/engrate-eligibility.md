---
api_specs:
- filename: engrate-audit-logs-api-openapi.yml
  format: yaml
  label: Engrate Audit Logs API
  slug: engrate-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-audit-logs-api-openapi.yml
- filename: engrate-benachrichtigung-api-openapi.yml
  format: yaml
  label: Engrate Benachrichtigung API
  slug: engrate-benachrichtigung-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-benachrichtigung-api-openapi.yml
- filename: engrate-betrieb-api-openapi.yml
  format: yaml
  label: Engrate Betrieb API
  slug: engrate-betrieb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-betrieb-api-openapi.yml
- filename: engrate-clearing-api-openapi.yml
  format: yaml
  label: Engrate Clearing API
  slug: engrate-clearing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-clearing-api-openapi.yml
- filename: engrate-core-api-openapi.yml
  format: yaml
  label: Engrate Core API
  slug: engrate-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-core-api-openapi.yml
- filename: engrate-cost-of-energy-api-openapi.yml
  format: yaml
  label: Engrate Cost Of Energy API
  slug: engrate-cost-of-energy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-cost-of-energy-api-openapi.yml
- filename: engrate-geo-api-openapi.yml
  format: yaml
  label: Engrate Geo API
  slug: engrate-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-geo-api-openapi.yml
- filename: engrate-holidays-api-openapi.yml
  format: yaml
  label: Engrate Holidays API
  slug: engrate-holidays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-holidays-api-openapi.yml
- filename: engrate-lokationen-api-openapi.yml
  format: yaml
  label: Engrate Lokationen API
  slug: engrate-lokationen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-lokationen-api-openapi.yml
- filename: engrate-lokationsb-ndel-api-openapi.yml
  format: yaml
  label: Engrate Lokationsbündel API
  slug: engrate-lokationsb-ndel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-lokationsb-ndel-api-openapi.yml
- filename: engrate-mabis-api-openapi.yml
  format: yaml
  label: Engrate Mabis API
  slug: engrate-mabis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-mabis-api-openapi.yml
- filename: engrate-netzbetreiberwechsel-api-openapi.yml
  format: yaml
  label: Engrate Netzbetreiberwechsel API
  slug: engrate-netzbetreiberwechsel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-netzbetreiberwechsel-api-openapi.yml
- filename: engrate-nl-settlement-api-openapi.yml
  format: yaml
  label: Engrate Nl Settlement API
  slug: engrate-nl-settlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-nl-settlement-api-openapi.yml
- filename: engrate-profiles-api-openapi.yml
  format: yaml
  label: Engrate Profiles API
  slug: engrate-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-profiles-api-openapi.yml
- filename: engrate-reference-api-openapi.yml
  format: yaml
  label: Engrate Reference API
  slug: engrate-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-reference-api-openapi.yml
- filename: engrate-schedules-api-openapi.yml
  format: yaml
  label: Engrate Schedules API
  slug: engrate-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-schedules-api-openapi.yml
- filename: engrate-status-request-api-openapi.yml
  format: yaml
  label: Engrate Status Request API
  slug: engrate-status-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-status-request-api-openapi.yml
- filename: engrate-time-series-api-openapi.yml
  format: yaml
  label: Engrate Time Series API
  slug: engrate-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-time-series-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - SE
    text: The Product enables the Client to calculate the total cost of electricity for any metering point or asset in Sweden.
  entity_types:
  - text: You represent to Engrate that you are lawfully able to enter into contracts (e.g., you are not a minor).
    type: individual
  - text: If you are entering into these Terms for an entity, such as the company you work for, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: You represent to Engrate that you are lawfully able to enter into contracts (e.g., you are not a minor).
    value: null
  restricted_uses:
  - summary: Full tariff structure display
    text: Displaying or distributing the full tariff structure (i.e., the complete set of tariff components, rules, and pricing parameters) to their own customers or any third parties.
  - summary: Bulk extraction or replication
    text: Copying, downloading, or extracting data from the Platform in bulk, or attempting to replicate or recreate Engrate’s data, data models, or integrations independently.
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
name: Engrate
provenance_date: '2026-11-09'
provider_name: Engrate
provider_slug: engrate
slug: engrate-eligibility
source_date: '2026-11-09'
source_filename: engrate-eligibility.yml
source_heading: Eligibility
source_page: https://engrate.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Engrate\naid: engrate\nurl: https://engrate.io/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SE\n  excluded: []\n  text: The Product enables the Client to calculate the total cost of electricity for any metering point or asset\n    in Sweden.\nentity_types:\n- type: individual\n  text: You represent to Engrate that you are lawfully able to enter into contracts (e.g., you are not a minor).\n- type: business\n  text: If you are entering into these Terms for an entity, such as the company you work for, you represent that\n    you have authority to bind that entity\nrestricted_uses:\n\
  - summary: Full tariff structure display\n  text: Displaying or distributing the full tariff structure (i.e., the complete set of tariff components, rules,\n    and pricing parameters) to their own customers or any third parties.\n- summary: Bulk extraction or replication\n  text: Copying, downloading, or extracting data from the Platform in bulk, or attempting to replicate or recreate\n    Engrate’s data, data models, or integrations independently.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent to Engrate that you are lawfully able to enter into contracts (e.g., you are not a minor).\n"
source_yaml_url: https://artifacts.apis.io/engrate/eligibility/engrate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Engrate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Platform
- Integration
- Markets
---
