---
api_specs:
- filename: alterauth-com-openapi-generated.yml
  format: yaml
  label: Alter API
  slug: alterauth-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alterauth-com/openapi/_ae-authored/alterauth-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is for business use and is not directed to children.
    type: business
  - text: You must be at least 18 years old and capable of forming a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract.
    value: '18'
  restricted_uses:
  - summary: Regulated data restrictions
    text: you must not use Customer-configurable storage, diagnostic payload capture, free-form fields, or support channels to persist protected health information regulated by HIPAA
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
name: Alter
provenance_date: '2026-11-09'
provider_name: Alter
provider_slug: alterauth-com
slug: alterauth-com-eligibility
source_date: '2026-11-09'
source_filename: alterauth-com-eligibility.yml
source_heading: Eligibility
source_page: https://alterauth.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alter\naid: alterauth-com\nurl: https://alterauth.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is for business use and is not directed to children.\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract.\nrestricted_uses:\n- summary: Regulated data restrictions\n  text: you must not use Customer-configurable storage, diagnostic payload capture, free-form fields, or support\n    channels to persist protected health information regulated by HIPAA\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/alterauth-com/eligibility/alterauth-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Alter's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Artificial Intelligence
- Privileged Access Management
- Identity and Access Management
- Privileged
---
