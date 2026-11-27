---
api_specs:
- filename: getaccept-archive-api-openapi.yml
  format: yaml
  label: GetAccept Archive API
  slug: getaccept-archive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-archive-api-openapi.yml
- filename: getaccept-attachments-api-openapi.yml
  format: yaml
  label: GetAccept Attachments API
  slug: getaccept-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-attachments-api-openapi.yml
- filename: getaccept-authentication-api-openapi.yml
  format: yaml
  label: GetAccept Authentication API
  slug: getaccept-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-authentication-api-openapi.yml
- filename: getaccept-communication-templates-api-openapi.yml
  format: yaml
  label: GetAccept Communication Templates API
  slug: getaccept-communication-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-communication-templates-api-openapi.yml
- filename: getaccept-contacts-api-openapi.yml
  format: yaml
  label: GetAccept Contacts API
  slug: getaccept-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-contacts-api-openapi.yml
- filename: getaccept-custom-data-api-openapi.yml
  format: yaml
  label: GetAccept Custom Data API
  slug: getaccept-custom-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-custom-data-api-openapi.yml
- filename: getaccept-documents-api-openapi.yml
  format: yaml
  label: GetAccept Documents API
  slug: getaccept-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-documents-api-openapi.yml
- filename: getaccept-others-api-openapi.yml
  format: yaml
  label: GetAccept Others API
  slug: getaccept-others-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-others-api-openapi.yml
- filename: getaccept-subscriptions-api-openapi.yml
  format: yaml
  label: GetAccept Subscriptions API
  slug: getaccept-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-subscriptions-api-openapi.yml
- filename: getaccept-templates-api-openapi.yml
  format: yaml
  label: GetAccept Templates API
  slug: getaccept-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-templates-api-openapi.yml
- filename: getaccept-users-api-openapi.yml
  format: yaml
  label: GetAccept Users API
  slug: getaccept-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-users-api-openapi.yml
- filename: getaccept-videos-api-openapi.yml
  format: yaml
  label: GetAccept Videos API
  slug: getaccept-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-videos-api-openapi.yml
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
  - summary: Unlawful purposes
    text: use the Services for any unlawful purpose
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
name: GetAccept
provenance_date: '2026-11-09'
provider_name: GetAccept
provider_slug: getaccept
slug: getaccept-eligibility
source_date: '2026-11-09'
source_filename: getaccept-eligibility.yml
source_heading: Eligibility
source_page: https://www.getaccept.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GetAccept\naid: getaccept\nurl: https://www.getaccept.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: use the Services for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getaccept/eligibility/getaccept-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from GetAccept's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Sales Enablement
- E-Signature
- Digital Sales Room
- Document Management
- Contract Management
- Proposals
- Software-as-a-Service
---
