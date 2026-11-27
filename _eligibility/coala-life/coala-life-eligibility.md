---
api_specs:
- filename: coala-life-patientsessions-api-openapi.yml
  format: yaml
  label: Coala Life Patient Sessions API
  slug: coala-life-patientsessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coala-life/openapi/coala-life-patientsessions-api-openapi.yml
- filename: coala-life-platform-api-api-openapi.yml
  format: yaml
  label: Coala Life Platform.Api API
  slug: coala-life-platform-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coala-life/openapi/coala-life-platform-api-api-openapi.yml
- filename: coala-life-sessions-api-openapi.yml
  format: yaml
  label: Coala Life Sessions API
  slug: coala-life-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coala-life/openapi/coala-life-sessions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You can only apply for a Coala subscription if you are 18 years of age or older.
    type: individual
  minimum_age:
    text: You can only apply for a Coala subscription if you are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Not for diagnosis of chest pain
    text: Please note that no Coala services are applicable for the diagnosis of chest pain.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: we reserve the right to make a prior approval and credit check before accepting payments.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coala Life
provenance_date: '2026-11-09'
provider_name: Coala Life
provider_slug: coala-life
slug: coala-life-eligibility
source_date: '2026-11-09'
source_filename: coala-life-eligibility.yml
source_heading: Eligibility
source_page: https://coalasolutions.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coala Life\naid: coala-life\nurl: https://coalasolutions.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You can only apply for a Coala subscription if you are 18 years of age or older.\nrestricted_uses:\n- summary: Not for diagnosis of chest pain\n  text: Please note that no Coala services are applicable for the diagnosis of chest pain.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: we reserve the right to make a prior approval and credit check before accepting payments.\nminimum_age:\n  value:\
  \ '18'\n  text: You can only apply for a Coala subscription if you are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/coala-life/eligibility/coala-life-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Coala Life's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Cardiology
- Remote Monitoring
- Digital Health
---
