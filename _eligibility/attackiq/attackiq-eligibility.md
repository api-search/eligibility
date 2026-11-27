---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: a resident of any country subject to a United States embargo or other similar United States export restrictions
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use limited to Purpose
    text: Customer may not use the Service or Content Library in any manner or for any purpose other than the Purpose and as expressly permitted by this Agreement.
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
name: AttackIQ
provenance_date: '2026-11-09'
provider_name: AttackIQ
provider_slug: attackiq
slug: attackiq-eligibility
source_date: '2026-11-09'
source_filename: attackiq-eligibility.yml
source_heading: Eligibility
source_page: https://www.attackiq.com/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AttackIQ\naid: attackiq\nurl: https://www.attackiq.com/eula/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: a resident of any country subject to a United States embargo or other similar United States export restrictions\nentity_types: []\nrestricted_uses:\n- summary: Use limited to Purpose\n  text: Customer may not use the Service or Content Library in any manner or for any purpose other than the Purpose\n    and as expressly permitted by this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/attackiq/eligibility/attackiq-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from AttackIQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Breach and Attack Simulation
- Continuous Threat Exposure Management
- Security Validation
- MITRE ATT&CK
- Threat Exposure Management
---
