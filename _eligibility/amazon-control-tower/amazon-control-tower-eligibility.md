---
api_specs:
- filename: amazon-control-tower-baselines-api-openapi.yml
  format: yaml
  label: Amazon Control Tower Baselines API
  slug: amazon-control-tower-baselines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-control-tower/openapi/amazon-control-tower-baselines-api-openapi.yml
- filename: amazon-control-tower-controls-api-openapi.yml
  format: yaml
  label: Amazon Control Tower Controls API
  slug: amazon-control-tower-controls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-control-tower/openapi/amazon-control-tower-controls-api-openapi.yml
- filename: amazon-control-tower-landing-zones-api-openapi.yml
  format: yaml
  label: Amazon Control Tower Landing Zones API
  slug: amazon-control-tower-landing-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-control-tower/openapi/amazon-control-tower-landing-zones-api-openapi.yml
- filename: amazon-control-tower-tags-api-openapi.yml
  format: yaml
  label: Amazon Control Tower Tags API
  slug: amazon-control-tower-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-control-tower/openapi/amazon-control-tower-tags-api-openapi.yml
claim_count: 1
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
  - summary: Spend limits not for critical use
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems
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
name: Amazon Control Tower
provenance_date: '2026-11-09'
provider_name: Amazon Control Tower
provider_slug: amazon-control-tower
slug: amazon-control-tower-eligibility
source_date: '2026-11-09'
source_filename: amazon-control-tower-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Control Tower\naid: amazon-control-tower\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spend limits not for critical use\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-control-tower/eligibility/amazon-control-tower-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amazon Control Tower's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Compliance
- Governance
- Landing Zone
- Multi-Account
- Security
- Control
---
