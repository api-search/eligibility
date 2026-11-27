---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Services on behalf of an organization, you represent that you have authority to bind that organization, and "you" refers to that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: Use the Services for any high-risk activity where failure of the Services could reasonably be expected to lead to death, bodily injury, or environmental damage.
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
name: Jarmin
provenance_date: '2026-11-09'
provider_name: Jarmin
provider_slug: jarmin
slug: jarmin-eligibility
source_date: '2026-11-09'
source_filename: jarmin-eligibility.yml
source_heading: Eligibility
source_page: https://www.jarmin.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jarmin\naid: jarmin\nurl: https://www.jarmin.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Services on behalf of an organization, you represent that you have authority to\n    bind that organization, and \"you\" refers to that organization.\nrestricted_uses:\n- summary: High-risk activities\n  text: Use the Services for any high-risk activity where failure of the Services could reasonably be expected to\n    lead to death, bodily injury, or environmental damage.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/jarmin/eligibility/jarmin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Jarmin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agentic Systems
- Machine Learning
- Automation
- AI Employees
- Y Combinator
---
