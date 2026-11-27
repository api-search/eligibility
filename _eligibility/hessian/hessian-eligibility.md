---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18+ and authorized to bind your company.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to enter into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful use or malware
    text: use the Service unlawfully, to develop or distribute malware, to send spam, or to interfere with the security or integrity of the Service or other users
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Access is currently invite-only, and we may decline to register or continue serving any prospective or existing customer in our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hessian
provenance_date: '2026-11-09'
provider_name: Hessian
provider_slug: hessian
slug: hessian-eligibility
source_date: '2026-11-09'
source_filename: hessian-eligibility.yml
source_heading: Eligibility
source_page: https://hessian.sh/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hessian\naid: hessian\nurl: https://hessian.sh/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must be 18+ and authorized to bind your company.\nrestricted_uses:\n- summary: Unlawful use or malware\n  text: use the Service unlawfully, to develop or distribute malware, to send spam, or to interfere with the security\n    or integrity of the Service or other users\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Access is currently invite-only, and we may decline to register or continue serving\
  \ any prospective or existing\n    customer in our sole discretion.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/hessian/eligibility/hessian-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Hessian's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Automation
- Workflow Automation
- Y Combinator
- Forward Deployed
---
