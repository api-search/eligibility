---
api_specs:
- filename: brightsec-com-openapi-generated.yml
  format: yaml
  label: brightsec-com API
  slug: brightsec-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightsec-com/openapi/_ae-authored/brightsec-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the individual accepting this Agreement lacks such authority, the Customer may not access or use the platform or services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive or regulated data
    text: upload, transmit, or otherwise make accessible to the Platform any sensitive or regulated data, including but not limited to personal health information, financial information, or government-issued identifiers
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
name: brightsec-com
provenance_date: '2026-11-09'
provider_name: brightsec-com
provider_slug: brightsec-com
slug: brightsec-com-eligibility
source_date: '2026-11-09'
source_filename: brightsec-com-eligibility.yml
source_heading: Eligibility
source_page: https://brightsec.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: brightsec-com\naid: brightsec-com\nurl: https://brightsec.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the individual accepting this Agreement lacks such authority, the Customer may not access or use the\n    platform or services.\nrestricted_uses:\n- summary: No sensitive or regulated data\n  text: upload, transmit, or otherwise make accessible to the Platform any sensitive or regulated data, including\n    but not limited to personal health information, financial information, or government-issued identifiers\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brightsec-com/eligibility/brightsec-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from brightsec-com's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Application Security
- DAST
- Artificial Intelligence
- API Testing
---
