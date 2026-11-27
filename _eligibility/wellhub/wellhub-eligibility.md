---
api_specs:
- filename: wellhub-companies-api-openapi.yml
  format: yaml
  label: Wellhub Companies API
  slug: wellhub-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wellhub/openapi/wellhub-companies-api-openapi.yml
- filename: wellhub-employees-api-openapi.yml
  format: yaml
  label: Wellhub Employees API
  slug: wellhub-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wellhub/openapi/wellhub-employees-api-openapi.yml
- filename: wellhub-jobs-api-openapi.yml
  format: yaml
  label: Wellhub Jobs API
  slug: wellhub-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wellhub/openapi/wellhub-jobs-api-openapi.yml
- filename: wellhub-oauth-api-openapi.yml
  format: yaml
  label: Wellhub O Auth API
  slug: wellhub-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wellhub/openapi/wellhub-oauth-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you live in Brazil, this contract is between you and GPBR PARTICIPAÇÕES LTDA.
  entity_types:
  - text: You must be at least 16 years of age or the age of legal majority in your jurisdiction (if different than 16) to register for Wellhub as a primary account holder and become a Wellhub Member.
    type: individual
  - text: You cannot enroll in a Wellhub Subscription to access the Wellhub Services as a primary account holder unless you are provided access through a participating organization such as, for example, your employer
    type: business
  minimum_age:
    text: You must be at least 16 years of age or the age of legal majority in your jurisdiction (if different than 16)
    value: '16'
  restricted_uses:
  - summary: No commercial or promotional use
    text: You may use the Services only for personal, noncommercial purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Wellhub reserves the right to validate the data that you provide us at any time, and we may request any additional information that we deem relevant in order to verify the information that you have provided.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wellhub
provenance_date: '2026-11-10'
provider_name: Wellhub
provider_slug: wellhub
slug: wellhub-eligibility
source_date: '2026-11-10'
source_filename: wellhub-eligibility.yml
source_heading: Eligibility
source_page: https://wellhub.com/en-us/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wellhub\naid: wellhub\nurl: https://wellhub.com/en-us/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you live in Brazil, this contract is between you and GPBR PARTICIPAÇÕES LTDA.\nentity_types:\n- type: individual\n  text: You must be at least 16 years of age or the age of legal majority in your jurisdiction (if different than\n    16) to register for Wellhub as a primary account holder and become a Wellhub Member.\n- type: business\n  text: You cannot enroll in a Wellhub Subscription to access the Wellhub Services as a primary account holder unless\n    you are provided\
  \ access through a participating organization such as, for example, your employer\nrestricted_uses:\n- summary: No commercial or promotional use\n  text: You may use the Services only for personal, noncommercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Wellhub reserves the right to validate the data that you provide us at any time, and we may request any\n    additional information that we deem relevant in order to verify the information that you have provided.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age or the age of legal majority in your jurisdiction (if different than\n    16)\n"
source_yaml_url: https://artifacts.apis.io/wellhub/eligibility/wellhub-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Wellhub's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Wellbeing
- Corporate Benefits
- Fitness
- Human Resources
- Eligibility
- Employee Benefits
---
