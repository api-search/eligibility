---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you represent a company, you confirm you are authorized to act on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification badges and trust markers are based on information available during review. BizClaw may revoke verification when material facts change, abuse is detected, or documentation is invalid.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BizClaw
provenance_date: '2026-11-09'
provider_name: BizClaw
provider_slug: bizclaw-xyz
slug: bizclaw-xyz-eligibility
source_date: '2026-11-09'
source_filename: bizclaw-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://bizclaw.xyz/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BizClaw\naid: bizclaw-xyz\nurl: https://bizclaw.xyz/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you represent a company, you confirm you are authorized to act on its behalf.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification badges and trust markers are based on information available during review. BizClaw may revoke\n    verification when material facts change, abuse is detected, or documentation is invalid.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bizclaw-xyz/eligibility/bizclaw-xyz-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from BizClaw's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Business
- Directory
- MCP
- REST API
- Discovery
---
