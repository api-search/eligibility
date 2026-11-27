---
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
  - summary: Unlawful or prohibited purposes
    text: You may not use our themes or Services for any unlawful or prohibited purpose, including but not limited to distributing malware, engaging in hacking, or violating any applicable laws.
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
name: DBSync
provenance_date: '2026-11-10'
provider_name: DBSync
provider_slug: mydbsync
slug: mydbsync-eligibility
source_date: '2026-11-10'
source_filename: mydbsync-eligibility.yml
source_heading: Eligibility
source_page: https://www.mydbsync.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DBSync\naid: mydbsync\nurl: https://www.mydbsync.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited purposes\n  text: You may not use our themes or Services for any unlawful or prohibited purpose, including but not limited\n    to distributing malware, engaging in hacking, or violating any applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mydbsync/eligibility/mydbsync-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from DBSync's own page on 2026-11-10.
synthetic: false
tags:
- Data Integration
- Replication
- Cloud Workflow
- AI Agents
- Enterprise
---
