---
api_specs:
- filename: airtable-bases-api-openapi.yml
  format: yaml
  label: Airtable Bases API
  slug: airtable-bases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airtable/openapi/airtable-bases-api-openapi.yml
- filename: airtable-comments-api-openapi.yml
  format: yaml
  label: Airtable Comments API
  slug: airtable-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airtable/openapi/airtable-comments-api-openapi.yml
- filename: airtable-fields-api-openapi.yml
  format: yaml
  label: Airtable Fields API
  slug: airtable-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airtable/openapi/airtable-fields-api-openapi.yml
- filename: airtable-groups-api-openapi.yml
  format: yaml
  label: Airtable Groups API
  slug: airtable-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airtable/openapi/airtable-groups-api-openapi.yml
- filename: airtable-records-api-openapi.yml
  format: yaml
  label: Airtable Records API
  slug: airtable-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airtable/openapi/airtable-records-api-openapi.yml
- filename: airtable-tables-api-openapi.yml
  format: yaml
  label: Airtable Tables API
  slug: airtable-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airtable/openapi/airtable-tables-api-openapi.yml
- filename: airtable-users-api-openapi.yml
  format: yaml
  label: Airtable Users API
  slug: airtable-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airtable/openapi/airtable-users-api-openapi.yml
- filename: airtable-webhooks-api-openapi.yml
  format: yaml
  label: Airtable Webhooks API
  slug: airtable-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airtable/openapi/airtable-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Neither you, nor any person to which you make our Services available or that is acting on your behalf, ... is (ii) located within or a resident of, or a segment of the government of, any country or territory for which the United States maintains trade and economic sanctions or embargoes.
  entity_types:
  - text: To use our Services, you must be at least 16 years old
    type: individual
  - text: If you are an individual and you access or use our Services on behalf of a company, organization, principal, or other entity, such as your employer
    type: business
  minimum_age:
    text: To use our Services, you must be at least 16 years old, and in some circumstances even older
    value: '16'
  restricted_uses:
  - summary: Trial features for testing only
    text: TRIAL FEATURES ARE PROVIDED TO YOU FOR TESTING PURPOSES ONLY
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
name: Airtable
provenance_date: '2026-11-09'
provider_name: Airtable
provider_slug: airtable
slug: airtable-eligibility
source_date: '2026-11-09'
source_filename: airtable-eligibility.yml
source_heading: Eligibility
source_page: https://www.airtable.com/company/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airtable\naid: airtable\nurl: https://www.airtable.com/company/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Neither you, nor any person to which you make our Services available or that is acting on your behalf, ...\n    is (ii) located within or a resident of, or a segment of the government of, any country or territory for which\n    the United States maintains trade and economic sanctions or embargoes.\nentity_types:\n- type: individual\n  text: To use our Services, you must be at least 16 years old\n- type: business\n  text: If you are an individual and\
  \ you access or use our Services on behalf of a company, organization, principal,\n    or other entity, such as your employer\nrestricted_uses:\n- summary: Trial features for testing only\n  text: TRIAL FEATURES ARE PROVIDED TO YOU FOR TESTING PURPOSES ONLY\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: To use our Services, you must be at least 16 years old, and in some circumstances even older\n"
source_yaml_url: https://artifacts.apis.io/airtable/eligibility/airtable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Airtable's own page on 2026-11-09.
synthetic: false
tags:
- Application
- Collaboration
- Data
- Database
- Low-Code
- Productivity
- Spreadsheets
---
