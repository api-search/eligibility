---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of the Site is intended for individuals who are at least 18 years of age.
    type: individual
  minimum_age:
    text: Use of the Site is intended for individuals who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Use violating law
    text: Use the Site in any way that violates applicable federal, state, local, or international law or regulation
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
name: LLM.co
provenance_date: '2026-11-09'
provider_name: LLM.co
provider_slug: llm
slug: llm-eligibility
source_date: '2026-11-09'
source_filename: llm-eligibility.yml
source_heading: Eligibility
source_page: https://llm.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LLM.co\naid: llm\nurl: https://llm.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use of the Site is intended for individuals who are at least 18 years of age.\nrestricted_uses:\n- summary: Use violating law\n  text: Use the Site in any way that violates applicable federal, state, local, or international law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Use of the Site is intended for individuals who are at least 18 years of\
  \ age.\n"
source_yaml_url: https://artifacts.apis.io/llm/eligibility/llm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from LLM.co's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Private-LLM
- Enterprise
- Custom Development
---
