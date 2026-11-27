---
api_specs:
- filename: hawksoft-agencies-api-openapi.yml
  format: yaml
  label: HawkSoft Agencies API
  slug: hawksoft-agencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hawksoft/openapi/hawksoft-agencies-api-openapi.yml
- filename: hawksoft-attachments-api-openapi.yml
  format: yaml
  label: HawkSoft Attachments API
  slug: hawksoft-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hawksoft/openapi/hawksoft-attachments-api-openapi.yml
- filename: hawksoft-clients-api-openapi.yml
  format: yaml
  label: HawkSoft Clients API
  slug: hawksoft-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hawksoft/openapi/hawksoft-clients-api-openapi.yml
- filename: hawksoft-log-entries-api-openapi.yml
  format: yaml
  label: HawkSoft Log Entries API
  slug: hawksoft-log-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hawksoft/openapi/hawksoft-log-entries-api-openapi.yml
- filename: hawksoft-receipts-api-openapi.yml
  format: yaml
  label: HawkSoft Receipts API
  slug: hawksoft-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hawksoft/openapi/hawksoft-receipts-api-openapi.yml
claim_count: 2
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
  - summary: Restricted Persons
    text: Developer hereby warrants that Developer is not a Restricted Person.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: API is available to the Developer for an annual fee of $3000, which must be paid in advance of any access to or use of the API.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HawkSoft
provenance_date: '2026-11-09'
provider_name: HawkSoft
provider_slug: hawksoft
slug: hawksoft-eligibility
source_date: '2026-11-09'
source_filename: hawksoft-eligibility.yml
source_heading: Eligibility
source_page: https://www.hawksoft.com/terms/api/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HawkSoft\naid: hawksoft\nurl: https://www.hawksoft.com/terms/api/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Restricted Persons\n  text: Developer hereby warrants that Developer is not a Restricted Person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: API is available to the Developer for an annual fee of $3000, which must be paid in advance of any access\n    to or use of the API.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hawksoft/eligibility/hawksoft-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from HawkSoft's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Agency Management System
- AMS
- Insurtech
- Property and Casualty
- Partner API
- Gated API
---
