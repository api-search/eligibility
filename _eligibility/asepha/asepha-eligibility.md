---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Use of the Site by anyone under the age of 18 is prohibited.
    value: '18'
  restricted_uses:
  - summary: Protected health information
    text: You understand and agree that the Site is not intended to store personal information and/or protected health information of any patient or other third party
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
name: Asepha
provenance_date: '2026-11-09'
provider_name: Asepha
provider_slug: asepha
slug: asepha-eligibility
source_date: '2026-11-09'
source_filename: asepha-eligibility.yml
source_heading: Eligibility
source_page: https://www.asepha.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asepha\naid: asepha\nurl: https://www.asepha.ai/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Protected health information\n  text: You understand and agree that the Site is not intended to store personal information and/or protected health\n    information of any patient or other third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Use of the Site by anyone under the age of 18 is prohibited.\n"
source_yaml_url: https://artifacts.apis.io/asepha/eligibility/asepha-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Asepha's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Artificial Intelligence
- Workflow Automation
- AI Agents
- Medication Management
- Healthcare Compliance
---
