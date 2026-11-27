---
api_specs:
- filename: instapods-openapi-generated.yml
  format: yaml
  label: ExpressTech Systems API
  slug: instapods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapods/openapi/_ae-authored/instapods-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to create an account.
    value: '16'
  restricted_uses:
  - summary: Illegal, mining, spam, reselling
    text: Illegal activity - Any use that violates applicable laws or regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account to use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ExpressTech Systems
provenance_date: '2026-11-09'
provider_name: ExpressTech Systems
provider_slug: instapods
slug: instapods-eligibility
source_date: '2026-11-09'
source_filename: instapods-eligibility.yml
source_heading: Eligibility
source_page: https://instapods.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ExpressTech Systems\naid: instapods\nurl: https://instapods.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal, mining, spam, reselling\n  text: Illegal activity - Any use that violates applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create an account to use the Service.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/instapods/eligibility/instapods-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from ExpressTech Systems's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Deployment
- Cloud
- AI Integration
- Developer Tools
---
