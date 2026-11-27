---
api_specs:
- filename: churnsolution-com-openapi-generated.yml
  format: yaml
  label: Churn Solution API
  slug: churnsolution-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/churnsolution-com/openapi/_ae-authored/churnsolution-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is available only to individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: The Website is available only to individuals who are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Unlawful use prohibited
    text: User shall not use the Service or any Content for any purpose that is unlawful or prohibited by this Agreement.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As a condition to using certain products and services of the Service, User may be required to register with Churn Solution and select a password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Churn Solution
provenance_date: '2026-11-09'
provider_name: Churn Solution
provider_slug: churnsolution-com
slug: churnsolution-com-eligibility
source_date: '2026-11-09'
source_filename: churnsolution-com-eligibility.yml
source_heading: Eligibility
source_page: https://churnsolution.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Churn Solution\naid: churnsolution-com\nurl: https://churnsolution.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is available only to individuals who are at least 13 years old.\nrestricted_uses:\n- summary: Unlawful use prohibited\n  text: User shall not use the Service or any Content for any purpose that is unlawful or prohibited by this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As a condition to using certain products and services of the Service, User may\
  \ be required to register with\n    Churn Solution and select a password.\nminimum_age:\n  value: '13'\n  text: The Website is available only to individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/churnsolution-com/eligibility/churnsolution-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Churn Solution's own page on 2026-11-09.
synthetic: false
tags:
- Software-as-a-Service
- Customer Retention
- Artificial Intelligence
- Subscription Management
- Marketing
---
