---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Program is available to recipients with a valid mobile number in the United States.
  entity_types:
  - text: You must be the account holder for the mobile number you provide, or have authorization from the account holder.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: OSSIO
provenance_date: '2026-11-10'
provider_name: OSSIO
provider_slug: ossio
slug: ossio-eligibility
source_date: '2026-11-10'
source_filename: ossio-eligibility.yml
source_heading: Eligibility
source_page: https://ossio.io/ossio-sms-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OSSIO\naid: ossio\nurl: https://ossio.io/ossio-sms-terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Program is available to recipients with a valid mobile number in the United States.\nentity_types:\n- type: individual\n  text: You must be the account holder for the mobile number you provide, or have authorization from the account\n    holder.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ossio/eligibility/ossio-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from OSSIO's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Health
- Orthopedics
- Life Sciences
- Manufacturing
- MCP
- Agents
---
