---
api_specs:
- filename: mobly-activations-api-openapi.yml
  format: yaml
  label: Mob.ly Activations API
  slug: mobly-activations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobly/openapi/mobly-activations-api-openapi.yml
- filename: mobly-events-api-openapi.yml
  format: yaml
  label: Mob.ly Events API
  slug: mobly-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobly/openapi/mobly-events-api-openapi.yml
- filename: mobly-industryevents-api-openapi.yml
  format: yaml
  label: Mob.ly Industry Events API
  slug: mobly-industryevents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobly/openapi/mobly-industryevents-api-openapi.yml
- filename: mobly-leadactivityevents-api-openapi.yml
  format: yaml
  label: Mob.ly Lead Activity Events API
  slug: mobly-leadactivityevents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobly/openapi/mobly-leadactivityevents-api-openapi.yml
- filename: mobly-leads-api-openapi.yml
  format: yaml
  label: Mob.ly Leads API
  slug: mobly-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobly/openapi/mobly-leads-api-openapi.yml
- filename: mobly-tag-groups-api-openapi.yml
  format: yaml
  label: Mob.ly Tag Groups API
  slug: mobly-tag-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobly/openapi/mobly-tag-groups-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 years of age and are legally authorized to sign on behalf of and have authority to bind the Customer
    type: individual
  - text: will provide services (“Services”) to an entity or individual (“Customer” or “you”)
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Sensitive data restrictions
    text: Customer shall ensure that Customer Data do not contain any of the following categories of sensitive data
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
name: Mob.ly
provenance_date: '2026-11-10'
provider_name: Mob.ly
provider_slug: mobly
slug: mobly-eligibility
source_date: '2026-11-10'
source_filename: mobly-eligibility.yml
source_heading: Eligibility
source_page: https://www.getmobly.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mob.ly\naid: mobly\nurl: https://www.getmobly.com/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 years of age and are legally authorized to sign on behalf of and have authority to bind\n    the Customer\n- type: business\n  text: will provide services (“Services”) to an entity or individual (“Customer” or “you”)\nrestricted_uses:\n- summary: Sensitive data restrictions\n  text: Customer shall ensure that Customer Data do not contain any of the following categories of sensitive data\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/mobly/eligibility/mobly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mob.ly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Event
- Event Marketing
- Lead Capture
- Lead Enrichment
- B2B
- Marketing
- Go-To-Market
- Artificial Intelligence
- CRM
- Marketing Automation
- Trade Shows
- Data Enrichment
---
