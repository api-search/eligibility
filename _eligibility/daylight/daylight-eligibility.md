---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use our Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or security-compromising activity
    text: You will not use our Services to engage in any activity that may compromise security, violate laws, or infringe on the rights of others.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to create an account to access certain features.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Daylight
provenance_date: '2026-11-09'
provider_name: Daylight
provider_slug: daylight
slug: daylight-eligibility
source_date: '2026-11-09'
source_filename: daylight-eligibility.yml
source_heading: Eligibility
source_page: https://daylight.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Daylight\naid: daylight\nurl: https://daylight.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or security-compromising activity\n  text: You will not use our Services to engage in any activity that may compromise security, violate laws, or infringe\n    on the rights of others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to create an account to access certain features.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/daylight/eligibility/daylight-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Daylight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Managed Detection and Response
- MDR
- Threat Detection
- Incident Response
- AI Agents
- SOC
- MCP
---
