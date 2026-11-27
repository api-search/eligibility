---
api_specs:
- filename: casedev-api-openapi.json
  format: json
  label: Case.dev API API
  slug: case-dev-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casedev/openapi/_original/casedev-api-openapi.json
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not be prohibited from using the Services under applicable law
  entity_types:
  - text: Be at least 18 years of age (or the age of majority in your jurisdiction)
    type: individual
  - text: If you are using the Services on behalf of an organization, you represent that you are authorized to accept these Terms on behalf of that organization.
    type: business
  - text: If you are a US government entity, the Services are provided as "commercial items"
    type: government
  - text: 'The Payments Platform is available only to: Licensed attorneys and law firms'
    type: other
  minimum_age:
    text: Be at least 18 years of age (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Payments Platform eligibility
    text: 'The Payments Platform is available only to: Licensed attorneys and law firms'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Other qualified entities approved by case.dev
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Case.dev
provenance_date: '2026-11-09'
provider_name: Case.dev
provider_slug: casedev
slug: casedev-eligibility
source_date: '2026-11-09'
source_filename: casedev-eligibility.yml
source_heading: Eligibility
source_page: https://case.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Case.dev\naid: casedev\nurl: https://case.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not be prohibited from using the Services under applicable law\nentity_types:\n- type: individual\n  text: Be at least 18 years of age (or the age of majority in your jurisdiction)\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you are authorized to accept\n    these Terms on behalf of that organization.\n- type: government\n  text: If you are a US government entity, the Services are provided as \"commercial items\"\n- type:\
  \ other\n  text: 'The Payments Platform is available only to: Licensed attorneys and law firms'\nrestricted_uses:\n- summary: Payments Platform eligibility\n  text: 'The Payments Platform is available only to: Licensed attorneys and law firms'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Other qualified entities approved by case.dev\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/casedev/eligibility/casedev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Case.dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Tech
- Artificial Intelligence
- Platform
- Automation
---
