---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer will identify an administrative user name and password for Customer’s Company account.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company reserves the right to refuse registration of, or cancel passwords it deems inappropriate.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Doctor Droid
provenance_date: '2026-11-09'
provider_name: Doctor Droid
provider_slug: doctor-droid
slug: doctor-droid-eligibility
source_date: '2026-11-09'
source_filename: doctor-droid-eligibility.yml
source_heading: Eligibility
source_page: https://docs.drdroid.io/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doctor Droid\naid: doctor-droid\nurl: https://docs.drdroid.io/policies/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer will identify an administrative user name and password for Customer’s Company account.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Company reserves the right to refuse registration of, or cancel passwords it deems inappropriate.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/doctor-droid/eligibility/doctor-droid-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Doctor Droid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AIOps
- SRE
- Incident Response
- On-Call
- Observability
- DevOps
- Monitoring
- MCP
- Incident Management
---
