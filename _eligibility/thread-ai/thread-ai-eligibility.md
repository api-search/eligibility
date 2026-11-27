---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use our Site.
    value: '18'
  restricted_uses:
  - summary: No security violations or unauthorized access
    text: You will not violate or attempt to violate the security of the Site or Thread AI’s systems or network security, including, without limitation by (i) accessing data not intended for users of the Site or gaining unauthorized access to an account, server or any other computer system
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
name: Thread AI
provenance_date: '2026-11-10'
provider_name: Thread AI
provider_slug: thread-ai
slug: thread-ai-eligibility
source_date: '2026-11-10'
source_filename: thread-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.threadai.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thread AI\naid: thread-ai\nurl: https://www.threadai.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No security violations or unauthorized access\n  text: You will not violate or attempt to violate the security of the Site or Thread AI’s systems or network security,\n    including, without limitation by (i) accessing data not intended for users of the Site or gaining unauthorized\n    access to an account, server or any other computer system\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/thread-ai/eligibility/thread-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Thread AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Orchestration
- Workflow Automation
- Agents
- Enterprise
- Governance
- MLOps
---
