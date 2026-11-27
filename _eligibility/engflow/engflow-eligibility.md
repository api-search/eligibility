---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Individual users of this Site must be at least 18 years old to use the Site and capable of forming a binding contract with EngFlow.
    type: individual
  - text: If you are entering into this Agreement on behalf of your organization or entity, you represent that you have the authority to bind such organization or entity
    type: business
  minimum_age:
    text: Individual users of this Site must be at least 18 years old to use the Site
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties
    text: You agree and confirm that you are not, and are not accessing or using this Site on behalf of or for, a sanctioned individual, organization or entity under applicable law
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
name: EngFlow
provenance_date: '2026-11-09'
provider_name: EngFlow
provider_slug: engflow
slug: engflow-eligibility
source_date: '2026-11-09'
source_filename: engflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.engflow.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EngFlow\naid: engflow\nurl: https://www.engflow.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Individual users of this Site must be at least 18 years old to use the Site and capable of forming a binding\n    contract with EngFlow.\n- type: business\n  text: If you are entering into this Agreement on behalf of your organization or entity, you represent that you\n    have the authority to bind such organization or entity\nrestricted_uses:\n- summary: Sanctioned parties\n  text: You agree and confirm that you are not, and\
  \ are not accessing or using this Site on behalf of or for, a\n    sanctioned individual, organization or entity under applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Individual users of this Site must be at least 18 years old to use the Site\n"
source_yaml_url: https://artifacts.apis.io/engflow/eligibility/engflow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EngFlow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Remote Execution
- Remote Caching
- Build Systems
- Bazel
- CI/CD
- Developer Tools
- gRPC
- Protocol Buffers
- DevOps
- Continuous Integration
---
