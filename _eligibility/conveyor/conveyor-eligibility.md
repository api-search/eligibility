---
api_specs:
- filename: conveyor-single-question-api-openapi.yml
  format: yaml
  label: Conveyor Single Question API
  slug: conveyor-single-question-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conveyor/openapi/conveyor-single-question-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Products and Services are intended for business or professional use only.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age to use the Services.
    value: '18'
  restricted_uses:
  - summary: High risk activities
    text: THE SERVICES ARE NOT DESIGNED, MANUFACTURED, OR INTENDED FOR HIGH RISK ACTIVITIES.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We may, in our sole discretion, refuse to offer the Services to any person or entity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Conveyor
provenance_date: '2026-11-09'
provider_name: Conveyor
provider_slug: conveyor
slug: conveyor-eligibility
source_date: '2026-11-09'
source_filename: conveyor-eligibility.yml
source_heading: Eligibility
source_page: https://www.conveyor.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conveyor\naid: conveyor\nurl: https://www.conveyor.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Products and Services are intended for business or professional use only.\nrestricted_uses:\n- summary: High risk activities\n  text: THE SERVICES ARE NOT DESIGNED, MANUFACTURED, OR INTENDED FOR HIGH RISK ACTIVITIES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: We may, in our sole discretion, refuse to offer the Services to any person or entity\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least eighteen (18) years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/conveyor/eligibility/conveyor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Conveyor's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Security Questionnaire Automation
- RFP Automation
- Trust Center
- Customer Trust
- Compliance
- Knowledge Management
---
