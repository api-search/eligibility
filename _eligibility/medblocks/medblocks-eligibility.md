---
api_specs:
- filename: medblocks-certificates-api-openapi.yml
  format: yaml
  label: Medblocks Certificates API
  slug: medblocks-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-certificates-api-openapi.yml
- filename: medblocks-connections-api-openapi.yml
  format: yaml
  label: Medblocks Connections API
  slug: medblocks-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-connections-api-openapi.yml
- filename: medblocks-events-api-openapi.yml
  format: yaml
  label: Medblocks Events API
  slug: medblocks-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-events-api-openapi.yml
- filename: medblocks-feeds-api-openapi.yml
  format: yaml
  label: Medblocks Feeds API
  slug: medblocks-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-feeds-api-openapi.yml
- filename: medblocks-health-api-openapi.yml
  format: yaml
  label: Medblocks Health API
  slug: medblocks-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-health-api-openapi.yml
- filename: medblocks-launch-contexts-api-openapi.yml
  format: yaml
  label: Medblocks Launch Contexts API
  slug: medblocks-launch-contexts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-launch-contexts-api-openapi.yml
- filename: medblocks-patient-sessions-api-openapi.yml
  format: yaml
  label: Medblocks Patient Sessions API
  slug: medblocks-patient-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-patient-sessions-api-openapi.yml
- filename: medblocks-patients-api-openapi.yml
  format: yaml
  label: Medblocks Patients API
  slug: medblocks-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-patients-api-openapi.yml
- filename: medblocks-webhooks-api-openapi.yml
  format: yaml
  label: Medblocks Webhooks API
  slug: medblocks-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: These Terms and Conditions constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unauthorized or unlawful Medicare data use
    text: You agree that you will not attempt to access Medicare data that is not your own or that you are not authorized to access, and that you will not use Medicare data obtained through the Application for any unlawful purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Medblocks
provenance_date: '2026-11-10'
provider_name: Medblocks
provider_slug: medblocks
slug: medblocks-eligibility
source_date: '2026-11-10'
source_filename: medblocks-eligibility.yml
source_heading: Eligibility
source_page: https://medblocks.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Medblocks\naid: medblocks\nurl: https://medblocks.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: business\n  text: These Terms and Conditions constitute a legally binding agreement made between you, whether personally or\n    on behalf of an entity\nrestricted_uses:\n- summary: Unauthorized or unlawful Medicare data use\n  text: You agree that you will\
  \ not attempt to access Medicare data that is not your own or that you are not authorized\n    to access, and that you will not use Medicare data obtained through the Application for any unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to register with the Site.\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/medblocks/eligibility/medblocks-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Medblocks's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Healthcare
- FHIR
- openEHR
- Interoperability
- Electronic Health Records
- Patient Access
- Health Data
- SMART on FHIR
- Webhook
- MCP
- Company
---
