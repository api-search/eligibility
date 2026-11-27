---
api_specs:
- filename: 123formbuilder-accounts-api-openapi.yml
  format: yaml
  label: 123FormBuilder Accounts API
  slug: 123formbuilder-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/123formbuilder/openapi/123formbuilder-accounts-api-openapi.yml
- filename: 123formbuilder-forms-api-openapi.yml
  format: yaml
  label: 123FormBuilder Forms API
  slug: 123formbuilder-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/123formbuilder/openapi/123formbuilder-forms-api-openapi.yml
- filename: 123formbuilder-groups-api-openapi.yml
  format: yaml
  label: 123FormBuilder Groups API
  slug: 123formbuilder-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/123formbuilder/openapi/123formbuilder-groups-api-openapi.yml
- filename: 123formbuilder-login-api-openapi.yml
  format: yaml
  label: 123FormBuilder Login API
  slug: 123formbuilder-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/123formbuilder/openapi/123formbuilder-login-api-openapi.yml
- filename: 123formbuilder-users-api-openapi.yml
  format: yaml
  label: 123FormBuilder Users API
  slug: 123formbuilder-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/123formbuilder/openapi/123formbuilder-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The services provided by 123FormBuilder can be used by any person if the terms of service are respected.
    type: individual
  - text: Enterprise customers must provide a minimum of thirty (30) days’ written notice prior to the applicable renewal date.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: HIPAA features Enterprise-only
    text: Our HIPAA features are only available on our Enterprise plan.
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
name: 123FormBuilder
provenance_date: '2026-11-09'
provider_name: 123FormBuilder
provider_slug: 123formbuilder
slug: 123formbuilder-eligibility
source_date: '2026-11-09'
source_filename: 123formbuilder-eligibility.yml
source_heading: Eligibility
source_page: https://www.123formbuilder.com/termsofservice.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 123FormBuilder\naid: 123formbuilder\nurl: https://www.123formbuilder.com/termsofservice.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The services provided by 123FormBuilder can be used by any person if the terms of service are respected.\n- type: business\n  text: Enterprise customers must provide a minimum of thirty (30) days’ written notice prior to the applicable\n    renewal date.\nrestricted_uses:\n- summary: HIPAA features Enterprise-only\n  text: Our HIPAA features are only available on our Enterprise plan.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/123formbuilder/eligibility/123formbuilder-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from 123FormBuilder's own page on 2026-11-09.
synthetic: false
tags:
- Online Forms
- Form Builder
- Surveys
- Workflows
- Data Collection
- Submissions
- Webhook
- HIPAA
- GDPR
- Payments
---
