---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: our trust center requires the creation of a login and ensures only trusted contacts have access to our legal and security documents.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cyera
provenance_date: '2026-11-09'
provider_name: Cyera
provider_slug: cyera
slug: cyera-eligibility
source_date: '2026-11-09'
source_filename: cyera-eligibility.yml
source_heading: Eligibility
source_page: https://www.cyera.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cyera\naid: cyera\nurl: https://www.cyera.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: our trust center requires the creation of a login and ensures only trusted contacts have access to our legal\n    and security documents.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cyera/eligibility/cyera-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Cyera's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Data Security
- DSPM
- Data Security Posture Management
- Data Classification
- Cloud Security
- Compliance
- MCP
- AI Security
---
