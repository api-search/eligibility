---
api_specs:
- filename: opslevel-graph-ql-api-openapi.yml
  format: yaml
  label: OpsLevel Graph QL API
  slug: opslevel-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opslevel/openapi/opslevel-graph-ql-api-openapi.yml
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
  - summary: Compliance with applicable law and export controls
    text: You will only use the Platform in accordance with applicable law, including, without limitation all export control laws.
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
name: OpsLevel
provenance_date: '2026-11-10'
provider_name: OpsLevel
provider_slug: opslevel
slug: opslevel-eligibility
source_date: '2026-11-10'
source_filename: opslevel-eligibility.yml
source_heading: Eligibility
source_page: https://www.opslevel.com/legal/t4-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpsLevel\naid: opslevel\nurl: https://www.opslevel.com/legal/t4-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Compliance with applicable law and export controls\n  text: You will only use the Platform in accordance with applicable law, including, without limitation all export\n    control laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/opslevel/eligibility/opslevel-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from OpsLevel's own page on 2026-11-10.
synthetic: false
tags:
- Developer Portal
- Developer Tools
- DevOps
- Experience
- Internal Developer Portal
- Microservices
- Platform Engineering
- Service Catalog
- Service Maturity
---
