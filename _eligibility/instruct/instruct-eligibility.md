---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Software is intended solely for individuals who are at least 18 years of age.
    type: individual
  minimum_age:
    text: The Software is intended solely for individuals who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: that contains nudity, biometric data, violence, or other content that is sensitive or controversial;
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
name: Instruct
provenance_date: '2026-11-09'
provider_name: Instruct
provider_slug: instruct
slug: instruct-eligibility
source_date: '2026-11-09'
source_filename: instruct-eligibility.yml
source_heading: Eligibility
source_page: https://legal.instruct.ai/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Instruct\naid: instruct\nurl: https://legal.instruct.ai/eula\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Software is intended solely for individuals who are at least 18 years of age.\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: that contains nudity, biometric data, violence, or other content that is sensitive or controversial;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Software is intended solely for individuals who are\
  \ at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/instruct/eligibility/instruct-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Instruct's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Agents
- Productivity
- Workflows
- Integration
- Software-as-a-Service
---
