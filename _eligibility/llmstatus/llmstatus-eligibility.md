---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms, and "you" refers to that organization.
    type: business
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction, or have the consent of a parent or guardian, to use the Service.
    value: age of majority
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
name: LLM Status
provenance_date: '2026-11-09'
provider_name: LLM Status
provider_slug: llmstatus
slug: llmstatus-eligibility
source_date: '2026-11-09'
source_filename: llmstatus-eligibility.yml
source_heading: Eligibility
source_page: https://llmstatus.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LLM Status\naid: llmstatus\nurl: https://llmstatus.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization to these Terms, and \"you\" refers to that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be at least the age of majority in your jurisdiction, or have the consent of a parent\
  \ or guardian,\n    to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/llmstatus/eligibility/llmstatus-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from LLM Status's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Model
- Monitoring
- CLI
---
