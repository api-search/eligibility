---
api_specs:
- filename: asknicely-contacts-api-openapi.yml
  format: yaml
  label: AskNicely Contacts API
  slug: asknicely-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asknicely/openapi/asknicely-contacts-api-openapi.yml
- filename: asknicely-in-app-surveys-api-openapi.yml
  format: yaml
  label: AskNicely In-App Surveys API
  slug: asknicely-in-app-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asknicely/openapi/asknicely-in-app-surveys-api-openapi.yml
- filename: asknicely-responses-api-openapi.yml
  format: yaml
  label: AskNicely Responses API
  slug: asknicely-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asknicely/openapi/asknicely-responses-api-openapi.yml
- filename: asknicely-statistics-api-openapi.yml
  format: yaml
  label: AskNicely Statistics API
  slug: asknicely-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asknicely/openapi/asknicely-statistics-api-openapi.yml
- filename: asknicely-surveys-api-openapi.yml
  format: yaml
  label: AskNicely Surveys API
  slug: asknicely-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asknicely/openapi/asknicely-surveys-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If an individual is accepting the terms and conditions of the Agreement on behalf of a company or other legal entity, such individual represents that they have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: AskNicely’s direct competitors are prohibited from accessing the Services, except with AskNicely’s prior written consent.
  - summary: No solicitation from children under 16
    text: Customer will not use AskNicely Services to solicit any information from children under the age of 16
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
name: AskNicely
provenance_date: '2026-11-09'
provider_name: AskNicely
provider_slug: asknicely
slug: asknicely-eligibility
source_date: '2026-11-09'
source_filename: asknicely-eligibility.yml
source_heading: Eligibility
source_page: https://www.asknicely.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AskNicely\naid: asknicely\nurl: https://www.asknicely.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If an individual is accepting the terms and conditions of the Agreement on behalf of a company or other\n    legal entity, such individual represents that they have the authority to bind such entity\nrestricted_uses:\n- summary: Direct competitors barred\n  text: AskNicely’s direct competitors are prohibited from accessing the Services, except with AskNicely’s prior\n    written consent.\n- summary: No solicitation from children\
  \ under 16\n  text: Customer will not use AskNicely Services to solicit any information from children under the age of 16\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asknicely/eligibility/asknicely-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from AskNicely's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Experience
- NPS
- Surveys
- Feedback
- Reputation Management
- Software-as-a-Service
- Customer Success
- Reviews
- SMS
---
