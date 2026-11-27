---
api_specs:
- filename: amazon-config-aws-config-api-openapi.yml
  format: yaml
  label: Amazon Config AWS Config API
  slug: amazon-config-aws-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-config/openapi/amazon-config-aws-config-api-openapi.yml
- filename: amazon-config-connector-api-openapi.yml
  format: yaml
  label: Amazon Config Config Connector API
  slug: amazon-config-connector-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-config/openapi/amazon-config-connector-api-openapi.yml
- filename: amazon-config-operations-api-openapi.yml
  format: yaml
  label: Amazon Config Config Operations API
  slug: amazon-config-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-config/openapi/amazon-config-operations-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spend limits not for critical systems
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems
  - summary: Microsoft Software not for High Risk Use
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other modes of human mass transportation, nuclear or chemical facilities, life support systems
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
name: Amazon Config
provenance_date: '2026-11-09'
provider_name: Amazon Config
provider_slug: amazon-config
slug: amazon-config-eligibility
source_date: '2026-11-09'
source_filename: amazon-config-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Config\naid: amazon-config\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spend limits not for critical systems\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems\n- summary: Microsoft Software not for High Risk Use\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other\n    modes of\
  \ human mass transportation, nuclear or chemical facilities, life support systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-config/eligibility/amazon-config-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Amazon Config's own page on 2026-11-09.
synthetic: false
tags:
- Auditing
- Amazon Web Services
- Compliance
- Configuration Management
- Governance
- Security
---
