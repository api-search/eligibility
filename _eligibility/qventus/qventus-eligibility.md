---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years old
    type: individual
  - text: These Terms govern your use of the Site and apply to the individuals accessing the Site and any organizations for whom they act as agents or employees.
    type: business
  minimum_age:
    text: You are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Site only for lawful purposes and in accordance with these Terms.
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
name: Qventus
provenance_date: '2026-11-10'
provider_name: Qventus
provider_slug: qventus
slug: qventus-eligibility
source_date: '2026-11-10'
source_filename: qventus-eligibility.yml
source_heading: Eligibility
source_page: https://www.qventus.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qventus\naid: qventus\nurl: https://www.qventus.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years old\n- type: business\n  text: These Terms govern your use of the Site and apply to the individuals accessing the Site and any organizations\n    for whom they act as agents or employees.\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Site only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/qventus/eligibility/qventus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Qventus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health IT
- Hospital Operations
- Artificial Intelligence
- Automation
- Care Coordination
---
