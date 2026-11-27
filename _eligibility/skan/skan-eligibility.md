---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Service(s) are intended for use by enterprise customers (Subscriber).
    type: business
  minimum_age:
    text: Skan Inc does not knowingly collect any Personal Identifiable Information from children under the age of 18.
    value: '18'
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
name: Skan
provenance_date: '2026-11-10'
provider_name: Skan
provider_slug: skan
slug: skan-eligibility
source_date: '2026-11-10'
source_filename: skan-eligibility.yml
source_heading: Eligibility
source_page: https://www.skan.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skan\naid: skan\nurl: https://www.skan.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Service(s) are intended for use by enterprise customers (Subscriber).\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Skan Inc does not knowingly collect any Personal Identifiable Information from children under the age of\n    18.\n"
source_yaml_url: https://artifacts.apis.io/skan/eligibility/skan-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Skan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Process Intelligence
- Task Mining
- Process Mining
- AI Agents
- Enterprise Automation
- Workflow Intelligence
---
