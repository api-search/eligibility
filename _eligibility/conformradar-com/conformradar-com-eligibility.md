---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: It is intended for online retail professionals and their advisers.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Checks are free and require no account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ConformRadar
provenance_date: '2026-11-09'
provider_name: ConformRadar
provider_slug: conformradar-com
slug: conformradar-com-eligibility
source_date: '2026-11-09'
source_filename: conformradar-com-eligibility.yml
source_heading: Eligibility
source_page: https://conformradar.com/en/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ConformRadar\naid: conformradar-com\nurl: https://conformradar.com/en/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: It is intended for online retail professionals and their advisers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Checks are free and require no account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/conformradar-com/eligibility/conformradar-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from ConformRadar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- E-Commerce
- Regulatory Compliance
- GPSR
- Consumer Protection
- MCP
- AI Agents
- France
- European Union
---
