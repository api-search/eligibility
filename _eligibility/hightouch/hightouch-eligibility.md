---
api_specs:
- filename: hightouch-sources-api-openapi.yml
  format: yaml
  label: Hightouch Sources API
  slug: hightouch-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-sources-api-openapi.yml
- filename: hightouch-models-api-openapi.yml
  format: yaml
  label: Hightouch Models API
  slug: hightouch-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-models-api-openapi.yml
- filename: hightouch-destinations-api-openapi.yml
  format: yaml
  label: Hightouch Destinations API
  slug: hightouch-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-destinations-api-openapi.yml
- filename: hightouch-syncs-api-openapi.yml
  format: yaml
  label: Hightouch Syncs API
  slug: hightouch-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-syncs-api-openapi.yml
- filename: hightouch-campaigns-api-openapi.yml
  format: yaml
  label: Hightouch Campaigns API
  slug: hightouch-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-campaigns-api-openapi.yml
- filename: hightouch-events-api-openapi.yml
  format: yaml
  label: Hightouch Events API
  slug: hightouch-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-events-api-openapi.yml
- filename: hightouch-decision-engine-api-openapi.yml
  format: yaml
  label: Hightouch Decision Engine API
  slug: hightouch-decision-engine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-decision-engine-api-openapi.yml
- filename: hightouch-id-graphs-api-openapi.yml
  format: yaml
  label: Hightouch Id Graphs API
  slug: hightouch-id-graphs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-id-graphs-api-openapi.yml
- filename: hightouch-idr-api-openapi.yml
  format: yaml
  label: Hightouch Idr API
  slug: hightouch-idr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-idr-api-openapi.yml
- filename: hightouch-sync-sequences-api-openapi.yml
  format: yaml
  label: Hightouch Sync Sequences API
  slug: hightouch-sync-sequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-sync-sequences-api-openapi.yml
- filename: hightouch-signups-api-openapi.yml
  format: yaml
  label: Hightouch Signups API
  slug: hightouch-signups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-signups-api-openapi.yml
- filename: hightouch-sync-templates-api-openapi.yml
  format: yaml
  label: Hightouch Sync Templates API
  slug: hightouch-sync-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hightouch/openapi/hightouch-sync-templates-api-openapi.yml
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
  - summary: Messaging misuse
    text: Customer must not use the Services to send unlawful, misleading, fraudulent, harassing, defamatory, infringing, or otherwise prohibited messages
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
name: Hightouch
provenance_date: '2026-11-09'
provider_name: Hightouch
provider_slug: hightouch
slug: hightouch-eligibility
source_date: '2026-11-09'
source_filename: hightouch-eligibility.yml
source_heading: Eligibility
source_page: https://hightouch.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hightouch\naid: hightouch\nurl: https://hightouch.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Messaging misuse\n  text: Customer must not use the Services to send unlawful, misleading, fraudulent, harassing, defamatory, infringing,\n    or otherwise prohibited messages\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hightouch/eligibility/hightouch-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Hightouch's own page on 2026-11-09.
synthetic: false
tags:
- CDP
- Data Activation
- Reverse ETL
- Audience Management
- Identity Resolution
- Event Collection
- Marketing
- Advertising
- AI Agents
- Data Warehouse
- A2A
- Customer Data Platform
---
