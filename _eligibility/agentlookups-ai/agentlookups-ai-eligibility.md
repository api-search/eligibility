---
claim_count: 2
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
  - summary: Not consumer reports under FCRA
    text: This is not a consumer report under the Fair Credit Reporting Act or any state consumer-reporting law.
  - summary: Fair housing compliance
    text: If you sell, rent, broker, finance, insure, or advertise housing, you are responsible for following fair housing law, including the Fair Housing Act, in how you use these results.
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
name: agentlookups-ai
provenance_date: '2026-11-09'
provider_name: agentlookups-ai
provider_slug: agentlookups-ai
slug: agentlookups-ai-eligibility
source_date: '2026-11-09'
source_filename: agentlookups-ai-eligibility.yml
source_heading: Eligibility
source_page: https://agentlookups.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agentlookups-ai\naid: agentlookups-ai\nurl: https://agentlookups.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not consumer reports under FCRA\n  text: This is not a consumer report under the Fair Credit Reporting Act or any state consumer-reporting law.\n- summary: Fair housing compliance\n  text: If you sell, rent, broker, finance, insure, or advertise housing, you are responsible for following fair\n    housing law, including the Fair Housing Act, in how you use these results.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentlookups-ai/eligibility/agentlookups-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from agentlookups-ai's own page on 2026-11-09.
synthetic: false
tags:
- Public Records
- Consumer Tools
- Data
- Beta
---
