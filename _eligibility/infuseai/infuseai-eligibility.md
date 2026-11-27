---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms of Use for an entity, such as the company you work for, you warrant and represent that you have the authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violating law or building competing product
    text: use the Services in violation of any applicable law or regulation, in order to build a competitive product or service
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
name: InfuseAI
provenance_date: '2026-11-09'
provider_name: InfuseAI
provider_slug: infuseai
slug: infuseai-eligibility
source_date: '2026-11-09'
source_filename: infuseai-eligibility.yml
source_heading: Eligibility
source_page: https://reccehq.com/statements/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: InfuseAI\naid: infuseai\nurl: https://reccehq.com/statements/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms of Use for an entity, such as the company you work for, you warrant\n    and represent that you have the authority to bind that entity\nrestricted_uses:\n- summary: Violating law or building competing product\n  text: use the Services in violation of any applicable law or regulation, in order to build a competitive product\n    or service\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/infuseai/eligibility/infuseai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from InfuseAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Data Quality
- Data Engineering
- dbt
- MLOps
- Analytics Engineering
- Developer Tools
- Open Source
- Artificial Intelligence
---
