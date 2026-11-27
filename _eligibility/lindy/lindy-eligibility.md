---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated data (HIPAA, FISMA)
    text: the Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: GLBA-violating use
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lindy
provenance_date: '2026-11-09'
provider_name: Lindy
provider_slug: lindy
slug: lindy-eligibility
source_date: '2026-11-09'
source_filename: lindy-eligibility.yml
source_heading: Eligibility
source_page: https://www.lindy.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lindy\naid: lindy\nurl: https://www.lindy.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Industry-specific regulated data (HIPAA, FISMA)\n  text: the Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.),\
  \ so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: GLBA-violating use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/lindy/eligibility/lindy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Lindy's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- AI Automation
- MCP
- Workflow Automation
- Virtual Assistant
- Productivity
- Email
- Meetings
- Slack
- A2A
---
