---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are over 18 (eighteen) years of age and are fully able and competent to enter into the terms
    type: individual
  minimum_age:
    text: you are over 18 (eighteen) years of age
    value: '18'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: Use the Platform or Services to collect or obtain personal information
  - summary: Illegal or harmful content
    text: is illegal or violates or may violate any applicable laws, rules or regulations
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
name: UnifyApps
provenance_date: '2026-11-10'
provider_name: UnifyApps
provider_slug: unifyapps
slug: unifyapps-eligibility
source_date: '2026-11-10'
source_filename: unifyapps-eligibility.yml
source_heading: Eligibility
source_page: https://www.unifyapps.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UnifyApps\naid: unifyapps\nurl: https://www.unifyapps.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are over 18 (eighteen) years of age and are fully able and competent to enter into the terms\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: Use the Platform or Services to collect or obtain personal information\n- summary: Illegal or harmful content\n  text: is illegal or violates or may violate any applicable laws, rules or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are over 18 (eighteen) years of age\n"
source_yaml_url: https://artifacts.apis.io/unifyapps/eligibility/unifyapps-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from UnifyApps's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Integration Platform
- iPaaS
- Automation
- No-Code
- Enterprise
- Data Replication
- MCP
---
