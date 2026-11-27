---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A user or AI agent must have authority to act for the person or organisation it represents.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, fraudulent or sanctions-evading use
    text: Users must not use Rose Bounty for unlawful activity, fraud, credential abuse, harmful automation, interference with systems, sanctions evasion, deceptive activity, unauthorised access, or any activity prohibited by the Acceptable Use Policy.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Sensitive or exceptional actions may be paused for human review.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rose Bounty
provenance_date: '2026-11-09'
provider_name: Rose Bounty
provider_slug: agttglobal-org
slug: agttglobal-org-eligibility
source_date: '2026-11-09'
source_filename: agttglobal-org-eligibility.yml
source_heading: Eligibility
source_page: https://agttglobal.org/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rose Bounty\naid: agttglobal-org\nurl: https://agttglobal.org/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A user or AI agent must have authority to act for the person or organisation it represents.\nrestricted_uses:\n- summary: Unlawful, fraudulent or sanctions-evading use\n  text: Users must not use Rose Bounty for unlawful activity, fraud, credential abuse, harmful automation, interference\n    with systems, sanctions evasion, deceptive activity, unauthorised access, or any activity prohibited by the\n    Acceptable\
  \ Use Policy.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Sensitive or exceptional actions may be paused for human review.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agttglobal-org/eligibility/agttglobal-org-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Rose Bounty's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Verification
- Autonomous
- Payments
- Platform
---
