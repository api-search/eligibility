---
api_specs:
- filename: capable-run-openapi-generated.yml
  format: yaml
  label: Capable API
  slug: capable-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capable-run/openapi/_ae-authored/capable-run-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you represent that you and your Authorized Users are not subject to applicable sanctions and are not located in an embargoed territory
  entity_types:
  - text: If you accept these Terms on behalf of a company or other legal entity, you represent that you have authority to bind that entity
    type: business
  - text: Where an Authorized User contracts as a consumer and mandatory consumer-protection law grants a statutory right of withdrawal, that right is preserved.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competing product or competitor benchmarking
    text: (e) use the Services to build a competing product or to benchmark for a competitor;
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
name: Capable
provenance_date: '2026-11-09'
provider_name: Capable
provider_slug: capable-run
slug: capable-run-eligibility
source_date: '2026-11-09'
source_filename: capable-run-eligibility.yml
source_heading: Eligibility
source_page: https://capable.run/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capable\naid: capable-run\nurl: https://capable.run/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you represent that you and your Authorized Users are not subject to applicable sanctions and are not located\n    in an embargoed territory\nentity_types:\n- type: business\n  text: If you accept these Terms on behalf of a company or other legal entity, you represent that you have authority\n    to bind that entity\n- type: individual\n  text: Where an Authorized User contracts as a consumer and mandatory consumer-protection law grants a statutory\n    right\
  \ of withdrawal, that right is preserved.\nrestricted_uses:\n- summary: Competing product or competitor benchmarking\n  text: (e) use the Services to build a competing product or to benchmark for a competitor;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/capable-run/eligibility/capable-run-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Capable's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Artificial Intelligence
- MCP
- Software-as-a-Service
- Sales
---
