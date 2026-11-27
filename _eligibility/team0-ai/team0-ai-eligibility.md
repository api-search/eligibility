---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If your company has signed an order form or agreement with Team0, it applies too.
    type: business
  minimum_age:
    text: Be 18 years or older to use this Service
    value: '18'
  restricted_uses:
  - summary: Harmful agent use
    text: Use AI agents for automated harassment, misinformation, or deceptive purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Joining is invite-only. Your company's admins invite people by work email
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: team0-ai
provenance_date: '2026-11-10'
provider_name: team0-ai
provider_slug: team0-ai
slug: team0-ai-eligibility
source_date: '2026-11-10'
source_filename: team0-ai-eligibility.yml
source_heading: Eligibility
source_page: https://team0.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: team0-ai\naid: team0-ai\nurl: https://team0.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If your company has signed an order form or agreement with Team0, it applies too.\nrestricted_uses:\n- summary: Harmful agent use\n  text: Use AI agents for automated harassment, misinformation, or deceptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Joining is invite-only. Your company's admins invite people by work email\nminimum_age:\n  value: '18'\n  text: Be 18 years or older to use this\
  \ Service\n"
source_yaml_url: https://artifacts.apis.io/team0-ai/eligibility/team0-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from team0-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Knowledge Management
- Automation
---
