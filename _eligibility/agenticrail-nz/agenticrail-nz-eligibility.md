---
api_specs:
- filename: agenticrail-nz-enforcement-api-openapi.yml
  format: yaml
  label: AgenticRail Enforcement API
  slug: agenticrail-nz-enforcement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticrail-nz/openapi/agenticrail-nz-enforcement-api-openapi.yml
- filename: agenticrail-nz-evidence-api-openapi.yml
  format: yaml
  label: AgenticRail Evidence API
  slug: agenticrail-nz-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticrail-nz/openapi/agenticrail-nz-evidence-api-openapi.yml
- filename: agenticrail-nz-operational-api-openapi.yml
  format: yaml
  label: AgenticRail Operational API
  slug: agenticrail-nz-operational-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticrail-nz/openapi/agenticrail-nz-operational-api-openapi.yml
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
  - summary: No sole control in high-risk systems
    text: AgenticRail must not be used as the sole control mechanism in any system where failure could result in harm to individuals, financial loss, or legal or regulatory impact.
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
name: AgenticRail
provenance_date: '2026-11-09'
provider_name: AgenticRail
provider_slug: agenticrail-nz
slug: agenticrail-nz-eligibility
source_date: '2026-11-09'
source_filename: agenticrail-nz-eligibility.yml
source_heading: Eligibility
source_page: https://agenticrail.nz/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgenticRail\naid: agenticrail-nz\nurl: https://agenticrail.nz/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No sole control in high-risk systems\n  text: AgenticRail must not be used as the sole control mechanism in any system where failure could result in harm\n    to individuals, financial loss, or legal or regulatory impact.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agenticrail-nz/eligibility/agenticrail-nz-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AgenticRail's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Sequence Enforcement
- Cryptographic Receipts
- Compliance
---
